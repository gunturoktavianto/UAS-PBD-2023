
# ER MODEL

> **Referensi** : [Link Video Kuliah ER MODEL](https://youtube.com/playlist?list=PLoJAIIF7j9weUPGKl_0r3aEAalkurlXOH)

## 1. Intro

#### A. Design Phases

1. Initial phase (req. user)
2. Second phase (choosing a data model (ER DIAGRAM))
3. Final phase (nsert to DBMS)

#### B. Design Alternatives
avoid:  
1. Redundancy (atribut berulang)
2. Incompleteness (mau insert atribut baru)

#### C. Design Approaches

1. Entity Relationship Model
2. Normalization Theory (Next topic)

## 2. Entity & Relationship

![ER](image.png)
![](image-1.png)
![Alt text](image-2.png)

## 3. Degree of Relationship Set

1. Binary relationship (2 entity)
2. Non-binary relationship/Ternary relationship ( >2 entity)
![Alt text](image-3.png)

## 4. Complex Attributes

1. Simple
2. Composite
3. Multivalued
4. Derived  

![Alt text](image-5.png)

## 5. Mapping Cardinality

1. One to one
2. One to many
3. Many to one
4. Many to many  

![Alt text](image-6.png)

## 6. Total & Partial Participations

![Alt text](image-7.png)

Tenary cuma boleh cuma 1 arrow

## 7. Primary Key

Primary key di relationship sets:  
1. Many-to-many: PK gabungan
2. One-to-many: PK diambil dari si "Many"
3. many-to-one: PK diambil dari si "Many"
4. One-to-one: PK diambil dari salah satu

## 8. Weak Entity
![Alt text](image-8.png)

## 9. Redundant Attributes

![Alt text](image-9.png)

## 10. Specialization & Generalization

Specialization (top-down):
![Alt text](image-10.png)

Generalization(bottom-up):
![Alt text](image-11.png)


Design Constraints:
1. Condition-defined OR user-defined
2. Disjoint OR overlapping
3. Total OR partial
   
![Alt text](image-14.png)

## 11. Aggregation

![Alt text](image-15.png)

## 12. Design Issue

1. Redundant:![Alt text](image-16.png)
2. Multivalued:![Alt text](image-17.png)
3. Entity or attribute?: ![Alt text](image-18.png)
4. Entity or realtionship sets?: ![Alt text](image-19.png)
5. Decisions: ![Alt text](image-20.png)
6. Symbols: ![Alt text](image-21.png) ![Alt text](image-23.png)
   