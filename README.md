
<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 7.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


**Credit : @code.xam  (Follow : instagram)**

**                  @gitxam (Follow : instagram)  **

**                   @javaxam (Follow : instagram)  **

**Founder:  Subham** 

<p style="text-align: right">
<strong><span style="text-decoration:underline;">DBMS & SQL NOTES</span> </strong></p>



    **<span style="text-decoration:underline;">Database:</span> **A database is a collection of related data which represents some aspect of the real world. A database system is designed to be built and populated with data for a certain task.  \
 \


<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



    **<span style="text-decoration:underline;">Database Management System (DBMS)</span> **is a software for storing and retrieving users' data while considering appropriate security measures. It consists of a group of programs which manipulate the database. The DBMS accepts the request for data from an application and instructs the operating system to provide the specific data. In large systems, a DBMS helps users and other third-party software to store and retrieve data. 


    Database management systems were developed to handle the following difficulties of typical File-processing systems supported by conventional operating systems. 


    1. Data redundancy and inconsistency 


    2. Difficulty in accessing data 


    3. Data isolation – multiple files and formats 


    4. Integrity problems 


    5. Atomicity of updates 


    6. Concurrent access by multiple users 


    7. Security problems 


    

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



    **<span style="text-decoration:underline;">ER diagram:</span> **


        ● ER diagram or **Entity Relationship diagram **is a conceptual model that gives the graphical representation of the logical structure of the database. 

<p style="text-align: right">
● It shows all the constraints and relationships that exist among the different components. </p>



        ● An ER diagram is mainly composed of the following three components- Entity Sets, Attributes and Relationship Set. 



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



    ● Roll_no is a primary key that can identify each entity uniquely.


    ● Thus, by using a student's roll number, a student can be identified uniquely. 


    **<span style="text-decoration:underline;">Entity Set:</span> **


    An entity set is a set of the same type of entities. 


    **● Strong Entity Set: **


            **<code>o </code></strong>A strong entity set is an entity set that contains sufficient attributes to uniquely identify all its entities. 


        `o `In other words, a primary key exists for a strong entity set. 


        `o `Primary key of a strong entity set is represented by underlining it. 


    ● **Weak Entity Set: **


            `o `A weak entity set is an entity set that does not contain sufficient attributes to uniquely identify its entities. 


        `o `In other words, a primary key does not exist for a weak entity set. 


        `o `However, it contains a partial key called a discriminator. 


        `o `Discriminator can identify a group of entities from the entity set. 


        `o `Discriminator is represented by underlining with a dashed line. 


    **<span style="text-decoration:underline;">Relationship:</span> **


    A relationship is defined as an association among several entities. 


        ● **Unary Relationship Set - **Unary relationship set is a relationship set where only one entity set participates in a relationship set. 


        ● **Binary Relationship Set - **Binary relationship set is a relationship set where two entity sets participate in a relationship set. 


        ● **Ternary Relationship Set - **Ternary relationship set is a relationship set where three entity sets participate in a relationship set. 


        ● **N-ary Relationship Set - **N-ary relationship set is a relationship set where ‘n’ entity sets participate in a relationship set. 


    **<span style="text-decoration:underline;">Cardinality Constraint:</span> **


    Cardinality constraint defines the maximum number of relationship instances in which an entity can participate. 


        ● **One-to-One Cardinality - **An entity in set A can be associated with at most one entity in set B. An entity in set B can be associated with at most one entity in set A.


        **● One-to-Many Cardinality - **An entity in set A can be associated with any number (zero or more) of entities in set B. An entity in set B can be associated with at most one entity in set A. 


    **● Many-to-One Cardinality - **An entity in set A can be associated with at most one entity in set B. An entity in set B can be associated with any number of entities in set A. **● Many-to-Many Cardinality - **An entity in set A can be associated with any number (zero or more) of entities in set B. An entity in set B can be associated with any number (zero or more) of entities in set A. 


    **<span style="text-decoration:underline;">Attributes:</span> **


    Attributes are the descriptive properties which are owned by each entity of an Entity Set. **Types of Attributes: **


        ● **Simple Attributes - **Simple attributes are those attributes which cannot be divided further. Ex. Age 


        ● **Composite Attributes - **Composite attributes are those attributes which are composed of many other simple attributes. Ex. Name, Address 


    ● **Multi Valued Attributes - **Multi valued attributes are those attributes which can take more than one value for a given entity from an entity set. Ex. Mobile No, Email ID ● **Derived Attributes - **Derived attributes are those attributes which can be derived from other attribute(s). Ex. Age can be derived from DOB. 


        ● **Key Attributes - **Key attributes are those attributes which can identify an entity uniquely in an entity set. Ex. Roll No. 


    **<span style="text-decoration:underline;">Constraints:</span> **


    Relational constraints are the restrictions imposed on the database contents and operations. They ensure the correctness of data in the database. 


        **● Domain Constraint - **Domain constraint defines the domain or set of values for an attribute. It specifies that the value taken by the attribute must be the atomic value from its domain. 


        **● Tuple Uniqueness Constraint - **Tuple Uniqueness constraint specifies that all the tuples must be necessarily unique in any relation. 


        ● **Key Constraint - **All the values of the primary key must be unique. The value of the primary key must not be null. 


        ● **Entity Integrity Constraint - **Entity integrity constraint specifies that no attribute of primary key must contain a null value in any relation.


        ● **Referential Integrity Constraint - **It specifies that all the values taken by the foreign key must either be available in the relation of the primary key or be null. 


    **<span style="text-decoration:underline;">Closure of an Attribute Set:</span> **


    The set of all those attributes which can be functionally determined from an attribute set is called a closure of that attribute set. 


    **<span style="text-decoration:underline;">Keys:</span> **


    A key is a set of attributes that can identify each tuple uniquely in the given relation**. Types of Keys: **


        **● Super Key - **A superkey is a set of attributes that can identify each tuple uniquely in the given relation. A super key may consist of any number of attributes. 


        **● Candidate Key - **A set of minimal attribute(s) that can identify each tuple uniquely in the given relation is called a candidate key. 


        **● Primary Key - **A primary key is a candidate key that the database designer selects while designing the database. Primary Keys are unique and NOT NULL. 

<p style="text-align: right">


<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image4.png" width="" alt="alt_text" title="image_tooltip">
</p>



        **● Alternate Key - **Candidate keys that are left unimplemented or unused after implementing the primary key are called as alternate keys. 


        **● Foreign Key - **An attribute ‘X’ is called as a foreign key to some other attribute ‘Y’ when its values are dependent on the values of attribute ‘Y’. The relation in which attribute ‘Y’ is present is called as the referenced relation. The relation in which attribute ‘X’ is present is called as the referencing relation. 


        **● Composite Key - **A primary key composed of multiple attributes and not just a single attribute is called a composite key. 


        **● Unique Key - **It is unique for all the records of the table. Once assigned, its value cannot be changed i.e. it is non-updatable. It may have a NULL value.


    **<span style="text-decoration:underline;">Functional Dependency:</span> **


    In any relation, a functional dependency α → β holds if- Two tuples having same value of attribute α also have same value for attribute β. 


    **Types of Functional Dependency: **


    ● **Trivial Functional Dependencies – **


        `o `A functional dependency X → Y is said to be trivial if and only if Y ⊆ X. `o `Thus, if RHS of a functional dependency is a subset of LHS, then it is called a trivial functional dependency. 


    ● **Non-Trivial Functional Dependencies – **


        `o `A functional dependency X → Y is said to be non-trivial if and only if Y ⊄ X. `o `Thus, if there exists at least one attribute in the RHS of a functional dependency that is not a part of LHS, then it is called a non-trivial functional dependency. 


    **<span style="text-decoration:underline;">Decomposition of a Relation:</span> **


    The process of breaking up or dividing a single relation into two or more sub relations is called the decomposition of a relation. 


    **Properties of Decomposition: **


    **● Lossless Decomposition - **Lossless decomposition ensures 


        `o `No information is lost from the original relation during decomposition. **<code>o </code></strong>When the sub relations are joined back, the same relation is obtained that was decomposed. 


    **● Dependency Preservation - **Dependency preservation ensures 


        `o `None of the functional dependencies that hold on the original relation are lost. **<code>o </code></strong>The sub relations still hold or satisfy the functional dependencies of the original relation. 


    **Types of Decomposition: **


    **● Lossless Join Decomposition: **


            `o `Consider there is a relation R which is decomposed into sub relations R1, R2, …., Rn. 


            `o `This decomposition is called lossless join decomposition when the join of the sub relations results in the same relation R that was decomposed. 


            **<code>o </code></strong>For lossless join decomposition, we always have- R1 ⋈ R2 ⋈ R3 ……. ⋈ Rn = R where ⋈ is a natural join operator 


    **● Lossy Join Decomposition: **


            `o `Consider there is a relation R which is decomposed into sub relations R1, R2, …., Rn.


        `o `This decomposition is called lossy join decomposition when the join of the sub relations does not result in the same relation R that was decomposed. 


            `o `For lossy join decomposition, we always have- R1 ⋈ R2 ⋈ R3 ……. ⋈ Rn ⊃ R where ⋈ is a natural join operator 


    **<span style="text-decoration:underline;">Normalization:</span> **


    In DBMS, database normalization is a process of making the database consistent by- 


    ● Reducing the redundancies 


    ● Ensuring the integrity of data through lossless decomposition 


    **Normal Forms: **


        ● **First Normal Form (1NF) - **A given relation is called in First Normal Form (1NF) if each cell of the table contains only an atomic value i.e. if the attribute of every tuple is either single valued or a null value. 


        ● **Second Normal Form (2NF) - **A given relation is called in Second Normal Form (2NF) if and only if 


        `o `Relation already exists in 1NF. 


        `o `No partial dependency exists in the relation. 


            A → B is called a **partial dependency **if and only if- A is a subset of some candidate key and B is a non-prime attribute. 


        ● **Third Normal Form (3NF) - **A given relation is called in Third Normal Form (3NF) if and only if 


        `o `Relation already exists in 2NF. 


        `o `No transitive dependency exists for non-prime attributes. 


            A → B is called a **transitive dependency **if and only if- A is not a super key and B is a non-prime attribute. 


        ● **Boyce-Codd Normal Form - **A given relation is called in BCNF if and only if `o `Relation already exists in 3NF. 


            `o `For each non-trivial functional dependency ‘A → B’, A is a super key of the relation.


    

<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")
**<span style="text-decoration:underline;">Transaction:</span> **


    Transaction is a single logical unit of work formed by a set of operations. **Operations in Transaction: **


        ● **Read Operation - Read(A) **instruction will read the value of ‘A’ from the database and will store it in the buffer in main memory. 


        ● **Write Operation – Write(A) **will write the updated value of ‘A’ from the buffer to the database. 


    **Transaction States: **



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



    **● Active State – **


        `o `This is the first state in the life cycle of a transaction. 


            `o `A transaction is called in an active state as long as its instructions are getting executed. 


            **<code>o </code></strong>All the changes made by the transaction now are stored in the buffer in main memory. 


    **● Partially Committed State – **


            `o `After the last instruction of the transaction has been executed, it enters into a partially committed state. 

<p style="text-align: right">
<code>o </code>After entering this state, the transaction is considered to be partially committed.</p>



            **<code>o </code></strong>It is not considered fully committed because all the changes made by the transaction are still stored in the buffer in main memory. 


    **● Committed State – **


            `o `After all the changes made by the transaction have been successfully stored into the database, it enters into a committed state. 


        **<code>o </code></strong>Now, the transaction is considered to be fully committed. 


    **● Failed State – **


            `o `When a transaction is getting executed in the active state or partially committed state and some failure occurs due to which it becomes impossible to continue the execution, it enters into a failed state. 


    ● **Aborted State – **


            `o `After the transaction has failed and entered into a failed state, all the changes made by it have to be undone. 


            `o `To undo the changes made by the transaction, it becomes necessary to roll back the transaction. 


    `o `After the transaction has rolled back completely, it enters into an aborted state. ● **Terminated State – **


        `o `This is the last state in the life cycle of a transaction. 


        `o `After entering the committed state or aborted state, the transaction finally enters into a terminated state where its life cycle finally comes to an end. 


    **<span style="text-decoration:underline;">ACID Properties:</span> **


    To ensure the consistency of the database, certain properties are followed by all the transactions occurring in the system. These properties are called as **ACID Properties **of a transaction. 


    ● **Atomicity – **


            `o `This property ensures that either the transaction occurs completely or it does not occur at all. 


        `o `In other words, it ensures that no transaction occurs partially. 


    ● **Consistency – **


        `o `This property ensures that integrity constraints are maintained. 


            `o `In other words, it ensures that the database remains consistent before and after the transaction. 


    ● **Isolation – **


            `o `This property ensures that multiple transactions can occur simultaneously without causing any inconsistency.


            `o `The resultant state of the system after executing all the transactions is the same as the state that would be achieved if the transactions were executed serially one after the other. 


    ● **Durability – **


            `o `This property ensures that all the changes made by a transaction after its successful execution are written successfully to the disk. 


            `o `It also ensures that these changes exist permanently and are never lost even if there occurs a failure of any kind. 


    **<span style="text-decoration:underline;">Schedules:</span> **


    The order in which the operations of multiple transactions appear for execution is called as a schedule. 



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



    **● Serial Schedules – **


        `o `All the transactions execute serially one after the other. 


    `o `When one transaction executes, no other transaction is allowed to execute. **<code>o </code></strong>Serial schedules are always- Consistent, Recoverable, Cascadeless and Strict. <strong>● Non-Serial Schedules – </strong>


        `o `Multiple transactions execute concurrently. 

<p style="text-align: right">
<strong><code>o </code></strong>Operations of all the transactions are inter leaved or mixed with each other.</p>



            **<code>o </code></strong>Non-serial schedules are <strong>not </strong>always- Consistent, Recoverable, Cascadeless and Strict. 


    **Serializability – **


    ● Some non-serial schedules may lead to inconsistency of the database. **● **Serializability is a concept that helps to identify which non-serial schedules are correct and will maintain the consistency of the database. 


    **● Serializable Schedules – **


        `o `If a given non-serial schedule of ‘n’ transactions is equivalent to some serial schedule of ‘n’ transactions, then it is called as a serializable schedule. 


            **<code>o </code></strong>Serializable schedules are always- Consistent, Recoverable, Cascadeless and Strict. 


    **Types of Serializability – **


        **● Conflict Serializability **- If a given non-serial schedule can be converted into a serial schedule by swapping its non-conflicting operations, then it is called a conflict serializable schedule. 


        **● View Serializability - **If a given schedule is found to be viewed as equivalent to some serial schedule, then it is called a view serializable schedule. 


    **Non-Serializable Schedules – **


    ● A non-serial schedule which is not serializable is called a non-serializable schedule. ● A non-serializable schedule is not guaranteed to produce the same effect as produced by some serial schedule on any consistent database. 


        **● **Non-serializable schedules- may or may not be consistent, may or may not be recoverable. 


    **● Irrecoverable Schedules – **


        If in a schedule, 


        `o `A transaction performs a dirty read operation from an uncommitted transaction `o `And commits before the transaction from which it has read the value then such a schedule is known as an Irrecoverable Schedule. 


    **● Recoverable Schedules – **


        If in a schedule, 


        `o `A transaction performs a dirty read operation from an uncommitted transaction `o `And its commit operation is delayed till the uncommitted transaction either commits or roll backs 


        then such a schedule is known as a Recoverable Schedule.


    **Types of Recoverable Schedules – **


        **● Cascading Schedule - **If in a schedule, failure of one transaction causes several other dependent transactions to rollback or abort, then such a schedule is called as a Cascading Schedule or Cascading Rollback or Cascading Abort. 


        **● Cascadeless Schedule - **If in a schedule, a transaction is not allowed to read a data item until the last transaction that has written it is committed or aborted, then such a schedule is called as a Cascadeless Schedule. 


        **● Strict Schedule - **If in a schedule, a transaction is neither allowed to read nor write a data item until the last transaction that has written it is committed or aborted, then such a schedule is called as a Strict Schedule. 


    **<span style="text-decoration:underline;">Relational Algebra:</span> **


    Relational Algebra is a procedural query language which takes a relation as an input and generates a relation as an output.


<table>
  <tr>
   <td>
    <strong>Basic Operator </strong>
   </td>
   <td>
    <strong>Semantic</strong>
   </td>
  </tr>
  <tr>
   <td>
    <strong>σ(Selection) </strong>
   </td>
   <td>
    Select rows based on given condition
   </td>
  </tr>
  <tr>
   <td>
    <strong>∏(Projection) </strong>
   </td>
   <td>
    Project some columns
   </td>
  </tr>
  <tr>
   <td>
    <strong>X (Cross Product) </strong>
   </td>
   <td>
    Cross product of relations, returns <strong>m*n </strong>rows where m and n are number of rows in R1 and R2 respectively.
   </td>
  </tr>
  <tr>
   <td>
    <strong>U (Union) </strong>
   </td>
   <td>
    Return those tuples which are either in R1 or in R2. Max no. of rows returned <strong>= m+n </strong>and Min no. of rows returned = <strong>max(m,n)</strong>
   </td>
  </tr>
  <tr>
   <td>
    <strong>−(Minus) </strong>
   </td>
   <td>
    R1-R2 returns those tuples which are in R1 but not in R2. Max no. of rows returned = <strong>m </strong>and Min no. of rows returned = <strong>m-n</strong>
   </td>
  </tr>
  <tr>
   <td>
    <strong>ρ(Rename) </strong>
   </td>
   <td>
    Renaming a relation to another relation.
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>
    <strong>Extended Operator </strong>
   </td>
   <td>
    <strong>Semantic</strong>
   </td>
  </tr>
  <tr>
   <td>
    <strong>∩ (Intersection) </strong>
   </td>
   <td>
    Returns those tuples which are in both R1 and R2. Max no. of rows returned = min(m,n) and Min no. of rows returned = 0
   </td>
  </tr>
  <tr>
   <td>
    ⋈<sub><strong>c(Conditional Join) </strong></sub>
   </td>
   <td>
    Selection from two or more tables based on some condition (Cross product followed by selection)
   </td>
  </tr>
  <tr>
   <td>
    ⋈<strong>(Equi Join) </strong>
   </td>
   <td>
    It is a special case of conditional join when only equality conditions are applied between attributes.
   </td>
  </tr>
  <tr>
   <td>
    ⋈<strong>(Natural Join) </strong>
   </td>
   <td>
    In natural join, equality conditions on common attributes hold and duplicate attributes are removed by default. 
<p>

    <strong>Note: </strong>Natural Join is equivalent to cross product if two relations have no attribute in common and natural join of a relation R with itself will return R only.
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>
    ⟕<strong>(Left Outer Join) </strong>
   </td>
   <td>
    When applying join on two relations R and S, some tuples of R or S do not appear in the result set which does not satisfy the join conditions. But Left Outer Joins gives all tuples of R in the result set. The tuples of R which do not satisfy the join condition will have values as NULL for attributes of S.
   </td>
  </tr>
  <tr>
   <td>
    ⟖<strong>(Right Outer Join) </strong>
   </td>
   <td>
    When applying join on two relations R and S, some tuples of R or S do not appear in the result set which does not satisfy the join conditions. But Right Outer Joins gives all tuples of S in the result set. The tuples of S which do not satisfy the join condition will have values as NULL for attributes of R.
   </td>
  </tr>
  <tr>
   <td>
    ⟗(Full Outer Join) 
<p>

    /(Division Operator) 
   </td>
   <td>
    When applying join on two relations R and S, some tuples of R or S do not appear in the result set which does not satisfy the join conditions. But Full Outer Joins gives all tuples of S and all tuples of R in the result set. The tuples of S which do not satisfy the join condition will have values as NULL for attributes of R and vice <span style="text-decoration:underline;">versa.</span> 
<p>

    Division operator A/B will return those tuples in A which are associated with every tuple of B. <strong>Note: </strong>Attributes of B should be a proper subset of attributes of A. The attributes in A/B will be Attributes of A- Attribute of B.
   </td>
  </tr>
</table>



    **<span style="text-decoration:underline;">File Structures:</span> **


        ● **Primary Index: **A primary index is an ordered file, records of fixed length with two fields. First field is the same as the primary key as a data file and the second field is a pointer to the data block, where the key is available. The average number of block accesses using index = **log<sub>2 </sub>Bi + 1**, where Bi = number of index blocks. 


        ● **Clustering Index: **Clustering index is created on data file whose records are physically ordered on a non-key field (called Clustering field). 


        ● **Secondary Index: **Secondary index provides secondary means of accessing a file for which primary access already exists. 


    **<span style="text-decoration:underline;">B Trees</span> **

At every level , we have Key and Data Pointer and data pointer points to either block or record. 


    **Properties of B-Trees: **


    Root of B-tree can have children between **2 **and **P**, where P is Order of tree. **Order of tree **– Maximum number of children a node can have. 


    Internal node can have children between ⌈ **P/2 **⌉ and **P **


    Internal node can have keys between ⌈ **P/2 **⌉ **– 1 **and **P-1**


    **<span style="text-decoration:underline;">B+ Trees</span> **


    In B+ trees, the structure of leaf and non-leaf are different, so their order is. Order of non-leaf will be higher as compared to leaf nodes. 


    Searching time will be less in B+ trees, since it doesn’t have record pointers in non-leaf because of which depth will decrease. 

<p style="text-align: right">
<strong><span style="text-decoration:underline;">SQL</span> </strong></p>



    **<span style="text-decoration:underline;">DDL:</span> **


    DDL is short name of **Data Definition Language, **which deals with database schemas and descriptions, of how the data should reside in the database. 


        ● CREATE - to create a database and its objects like (table, index, views, store procedure, function, and triggers) 


    ● ALTER - alters the structure of the existing database 


    ● DROP - delete objects from the database 


        ● TRUNCATE - remove all records from a table, including all spaces allocated for the records are removed 


    ● RENAME - rename an object 


    **<span style="text-decoration:underline;">DML:</span> **


    DML is short name of **Data Manipulation Language **which deals with data manipulation and includes most common SQL statements such SELECT, INSERT, UPDATE, DELETE, etc., and it is used to store, modify, retrieve, delete and update data in a database. 


    ● SELECT - retrieve data from a database 


    ● INSERT - insert data into a table 


    ● UPDATE - updates existing data within a table 


    ● DELETE - Delete all records from a database table 


    ● MERGE - UPSERT operation (insert or update) 


    **<span style="text-decoration:underline;">DCL:</span>**


    DCL is short name of **Data Control Language **which includes commands such as GRANT and mostly concerned with rights, permissions and other controls of the database system. 


    ● GRANT - allow users access privileges to the database 


    ● REVOKE - withdraw users access privileges given by using the GRANT command 


    **<span style="text-decoration:underline;">TCL:</span> **


    TCL is short name of Transaction Control Language which deals with a transaction within a database. 


    ● COMMIT - commits a Transaction 


    ● ROLLBACK - rollback a transaction in case of any error occurs 


    ● SAVEPOINT - to roll back the transaction making points within groups **<span style="text-decoration:underline;">SQL:</span> **


    SQL is a standard language for storing, manipulating and retrieving data in databases. 


    **<span style="text-decoration:underline;">SELECT:</span> **


    The SELECT statement is used to select data from a database. 


    **Syntax - **


    ● SELECT _column1_, _column2, ... _


        FROM _table_name_; 


    ● Here, column1, column2, ... are the field names of the table you want to select data from. If you want to select all the fields available in the table, use the following syntax: ● SELECT * FROM _table_name_; 


    **Ex – **


    ● SELECT CustomerName, City FROM Customers; 


    **<span style="text-decoration:underline;">SELECT DISTINCT:</span> **


    The SELECT DISTINCT statement is used to return only distinct (different) values. **Syntax – **


    ● SELECT DISTINCT _column1_, _column2, ... _


        FROM _table_name_; 


    **Ex –**


    ● SELECT DISTINCT Country FROM Customers; 


    **<span style="text-decoration:underline;">WHERE:</span> **


    The WHERE clause is used to filter records. 


    **Syntax – **


    ● SELECT _column1_, _column2, ... _


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT * FROM Customers 


        WHERE Country='Mexico'; 


<table>
  <tr>
   <td>
    <strong>Operator </strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>
    = 
   </td>
   <td>
    Equal
   </td>
  </tr>
  <tr>
   <td>
    > 
   </td>
   <td>
    Greater than
   </td>
  </tr>
  <tr>
   <td>
    &lt; 
   </td>
   <td>
    Less than
   </td>
  </tr>
  <tr>
   <td>
    >= 
   </td>
   <td>
    Greater than or equal
   </td>
  </tr>
  <tr>
   <td>
    &lt;= 
   </td>
   <td>
    Less than or equal
   </td>
  </tr>
  <tr>
   <td>
    &lt;> 
   </td>
   <td>
    Not equal. <strong>Note: </strong>In some versions of SQL this operator may be written as !=
   </td>
  </tr>
</table>



    **<span style="text-decoration:underline;">AND, OR and NOT:</span> **


    The WHERE clause can be combined with AND, OR, and NOT operators. 


    The AND and OR operators are used to filter records based on more than one condition: 


    ● The AND operator displays a record if all the conditions separated by AND are TRUE. ● The OR operator displays a record if any of the conditions separated by OR is TRUE. 


    The NOT operator displays a record if the condition(s) is NOT TRUE. 


    **Syntax – **


    ● SELECT _column1_, _column2, ... _


        FROM _table_name _


        WHERE _condition1 _AND _condition2 _AND _condition3 ..._; 


    ● SELECT _column1_, _column2, ... _


        FROM _table_name _


        WHERE _condition1 _OR _condition2 _OR _condition3 ..._;


    ● SELECT _column1_, _column2, ... _


        FROM _table_name _


        WHERE NOT _condition_; 


    **Ex – **


    ● SELECT * FROM Customers 


        WHERE Country='Germany' AND City='Berlin'; 


    ● SELECT * FROM Customers 


        WHERE Country='Germany' AND (City='Berlin' OR City='München'); 


    **<span style="text-decoration:underline;">ORDER BY:</span> **


    The ORDER BY keyword is used to sort the result-set in ascending or descending order. 


    The ORDER BY keyword sorts the records in ascending order by default. To sort the records in descending order, use the DESC keyword. 


    **Syntax – **


    ● SELECT _column1_, _column2, ... _


        FROM _table_name _


        ORDER BY _column1, column2, ... _ASC|DESC; 


    **Ex – **


    ● SELECT * FROM Customers 


        ORDER BY Country; 


    ● SELECT * FROM Customers 


        ORDER BY Country ASC, CustomerName DESC; 


    **<span style="text-decoration:underline;">INSERT INTO:</span> **


    The INSERT INTO statement is used to insert new records in a table. 


    **Syntax – **


    ● INSERT INTO _table_name _(_column1_, _column2_, _column3_, ...) 


        VALUES (_value1_, _value2_, _value3_, ...); 


    ● INSERT INTO _table_name _


        VALUES (_value1_, _value2_, _value3_, ...); 


    *In the second syntax, make sure the order of the values is in the same order as the columns in the table.


    **Ex – **


        ● INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country) 


        VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway'); 


    **<span style="text-decoration:underline;">NULL Value:</span> **


    It is not possible to test for NULL values with comparison operators, such as =, &lt;, or &lt;>. We will have to use the IS NULL and IS NOT NULL operators instead. 


    **Syntax – **


    ● SELECT _column_names _


        FROM _table_name _


        WHERE _column_name _IS NULL; 


    ● SELECT _column_names _


        FROM _table_name _


        WHERE _column_name _IS NOT NULL; 


    **Ex – **


    ● SELECT CustomerName, ContactName, Address 


        FROM Customers 


        WHERE Address IS NULL; 


    **<span style="text-decoration:underline;">UPDATE:</span> **


    The UPDATE statement is used to modify the existing records in a table. **Syntax – **


    ● UPDATE _table_name _


        SET _column1 _= _value1_, _column2 _= _value2_, ... 


        WHERE _condition_; 


    **Ex – **


    ● UPDATE Customers 


        SET ContactName = 'Alfred Schmidt', City= 'Frankfurt' 


        WHERE CustomerID = 1;


    **<span style="text-decoration:underline;">DELETE:</span> **


    The DELETE statement is used to delete existing records in a table. 


    **Syntax – **


    ● DELETE FROM _table_name _WHERE _condition_; 


    ● DELETE FROM _table_name_; 


    In 2<sup>nd</sup>syntax, all rows are deleted. The table structure, attributes, and indexes will be intact **Ex – **


    ● DELETE FROM Customers WHERE CustomerName='Alfreds Futterkiste'; 


    **<span style="text-decoration:underline;">SELECT TOP:</span> **


    The SELECT TOP clause is used to specify the number of records to return. **Syntax – **


    ● SELECT TOP _number_|_percent column_name(s) _


        FROM _table_name _


        WHERE _condition_; 


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _condition _


        LIMIT _number_; 


    ● SELECT _column_name(s) _


        FROM _table_name _


        ORDER BY _column_name(s) _


        FETCH FIRST _number _ROWS ONLY; 


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE ROWNUM &lt;= _number_; 


    *In case the interviewer asks other than the TOP, rest are also correct. (Diff. DB Systems) **Ex – **


    ● SELECT TOP 3 * FROM Customers; 


    ● SELECT * FROM Customers 


        LIMIT 3; 


    ● SELECT * FROM Customers 


        FETCH FIRST 3 ROWS ONLY;


    **<span style="text-decoration:underline;">Aggregate Functions:</span> **


    **MIN(): **


    The MIN() function returns the smallest value of the selected column. **Syntax – **


    ● SELECT MIN(_column_name_) 


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT MIN(Price) AS SmallestPrice 


        FROM Products; 


    **MAX(): **


    The MAX() function returns the largest value of the selected column. **Syntax – **


    ● SELECT MAX(_column_name_) 


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT MAX(Price) AS LargestPrice 


        FROM Products; 


    **COUNT(): **


    The COUNT() function returns the number of rows that matches a specified criterion. **Syntax – **


    ● SELECT COUNT(_column_name_) 


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT COUNT(ProductID) 


        FROM Products; 


    **AVG():**


    The AVG() function returns the average value of a numeric column. 


    **Syntax – **


    ● SELECT AVG(_column_name_) 


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT AVG(Price) 


        FROM Products; 


    **SUM(): **


    The SUM() function returns the total sum of a numeric column. 


    **Syntax – **


    ● SELECT SUM(_column_name_) 


        FROM _table_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT SUM(Quantity) 


        FROM OrderDetails; 


    **<span style="text-decoration:underline;">LIKE Operator:</span> **


    The LIKE operator is used in a WHERE clause to search for a specified pattern in a column. There are two wildcards often used in conjunction with the LIKE operator: 


    ● The percent sign (%) represents zero, one, or multiple characters 


    ● The underscore sign (_) represents one, single character 


    **Syntax – **


    ● SELECT _column1, column2, ... _


        FROM _table_name _


        WHERE _columnN _LIKE _pattern_;


<table>
  <tr>
   <td>
    <strong>LIKE Operator </strong>
   </td>
   <td>
    <strong>Description</strong>
   </td>
  </tr>
  <tr>
   <td>
    WHERE CustomerName LIKE 'a%' 
   </td>
   <td>
    Finds any values that start with "a"
   </td>
  </tr>
  <tr>
   <td>
    WHERE CustomerName LIKE '%a' 
   </td>
   <td>
    Finds any values that end with "a"
   </td>
  </tr>
  <tr>
   <td>
    WHERE CustomerName LIKE '%or%' 
   </td>
   <td>
    Finds any values that have "or" in any position
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>
    WHERE CustomerName LIKE '_r%' 
   </td>
   <td>
    Finds any values that have "r" in the second position
   </td>
  </tr>
  <tr>
   <td>
    WHERE CustomerName LIKE 'a_%' 
   </td>
   <td>
    Finds any values that start with "a" and are at least 2 characters in length
   </td>
  </tr>
  <tr>
   <td>
    WHERE CustomerName LIKE 'a__%' 
   </td>
   <td>
    Finds any values that start with "a" and are at least 3 characters in length
   </td>
  </tr>
  <tr>
   <td>
    WHERE ContactName LIKE 'a%o' 
   </td>
   <td>Finds any values that start with "a" and ends with "o"
   </td>
  </tr>
</table>



    **<span style="text-decoration:underline;">IN:</span> **


    The IN operator allows you to specify multiple values in a WHERE clause. The IN operator is a shorthand for multiple OR conditions. 


    **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _column_name _IN (_value1_, _value2_, ...); 


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _column_name _IN (_SELECT STATEMENT_); 


    **Ex – **


    ● SELECT * FROM Customers 


        WHERE Country IN ('Germany', 'France', 'UK'); 


    ● SELECT * FROM Customers 


        WHERE Country IN (SELECT Country FROM Suppliers); 


    **<span style="text-decoration:underline;">BETWEEN:</span> **


    The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates. 


    The BETWEEN operator is inclusive: begin and end values are included. 


    **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _column_name _BETWEEN _value1 _AND _value2; _


    **Ex –**


    ● SELECT * FROM Products 


        WHERE Price BETWEEN 10 AND 20; 


    **<span style="text-decoration:underline;">Joins:</span> **


    A JOIN clause is used to combine rows from two or more tables, based on a related column between them. 


    **INNER JOIN: **


    The INNER JOIN keyword selects records that have matching values in both tables. **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table1 _


        INNER JOIN _table2 _


        ON _table1.column_name _= _table2.column_name_; 


    **Ex – **


    ● SELECT Orders.OrderID, Customers.CustomerName 


        FROM Orders 


        INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID; 


    **LEFT (OUTER) JOIN: **


    The LEFT JOIN keyword returns all records from the left table (table1), and the matching records from the right table (table2). The result is 0 records from the right side, if there is no match. 


    **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table1 _


        LEFT JOIN _table2 _


        ON _table1.column_name _= _table2.column_name_; 


    **Ex – **


    ● SELECT Customers.CustomerName, Orders.OrderID 


        FROM Customers 


        LEFT JOIN Orders ON Customers.CustomerID = Orders.CustomerID 


        ORDER BY Customers.CustomerName;


    **RIGHT (OUTER) JOIN: **


    The RIGHT JOIN keyword returns all records from the right table (table2), and the matching records from the left table (table1). The result is 0 records from the left side, if there is no match. 


    **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table1 _


        RIGHT JOIN _table2 _


        ON _table1.column_name _= _table2.column_name_; 


    **Ex – **


        ● SELECT Orders.OrderID, Employees.LastName, Employees.FirstName FROM Orders 


        RIGHT JOIN Employees ON Orders.EmployeeID = Employees.EmployeeID ORDER BY Orders.OrderID; 


    **FULL (OUTER) JOIN: **


    The FULL OUTER JOIN keyword returns all records when there is a match in left (table1) or right (table2) table records. 


    **Syntax: **


    ● SELECT _column_name(s) _


        FROM _table1 _


        FULL OUTER JOIN _table2 _


        ON _table1.column_name _= _table2.column_name _


        WHERE _condition_; 


    **Ex – **


    ● SELECT Customers.CustomerName, Orders.OrderID 


        FROM Customers 


        FULL OUTER JOIN Orders ON Customers.CustomerID=Orders.CustomerID ORDER BY Customers.CustomerName; 


    **<span style="text-decoration:underline;">UNION:</span> **


    The UNION operator is used to combine the result-set of two or more SELECT statements.


    ● Every SELECT statement within UNION must have the same number of columns ● The columns must also have similar data types 


    ● The columns in every SELECT statement must also be in the same order 


    The UNION operator selects only distinct values by default. To allow duplicate values, use UNION ALL 


    **Syntax – **


    ● SELECT _column_name(s) _FROM _table1 _


        UNION 


        SELECT _column_name(s) _FROM _table2_; 


    ● SELECT _column_name(s) _FROM _table1 _


        UNION ALL 


        SELECT _column_name(s) _FROM _table2_; 


    **Ex – **


    ● SELECT City FROM Customers 


        UNION 


        SELECT City FROM Suppliers 


        ORDER BY City; 


    **<span style="text-decoration:underline;">GROUP BY:</span> **


    The GROUP BY statement groups rows that have the same values into summary rows, like "find the number of customers in each country". 


    The GROUP BY statement is often used with aggregate functions 


    (COUNT(), MAX(), MIN(), SUM(), AVG()) to group the result-set by one or more columns. **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _condition _


        GROUP BY _column_name(s) _


        ORDER BY _column_name(s); _


    **Ex – **


    ● SELECT COUNT(CustomerID), Country 


        FROM Customers 


        GROUP BY Country 


        ORDER BY COUNT(CustomerID) DESC;


    **<span style="text-decoration:underline;">HAVING:</span> **


    The HAVING clause was added to SQL because the WHERE keyword cannot be used with aggregate functions. 


    *WHERE is given priority over HAVING. 


    **Syntax – **


    ● SELECT _column_name(s) _


        FROM _table_name _


        WHERE _condition _


        GROUP BY _column_name(s) _


        HAVING _condition _


        ORDER BY _column_name(s); _


    **Ex – **


    ● SELECT COUNT(CustomerID), Country 


        FROM Customers 


        GROUP BY Country 


        HAVING COUNT(CustomerID) > 5; 


    **<span style="text-decoration:underline;">CREATE DATABASE:</span> **


    The CREATE DATABASE statement is used to create a new SQL database. **Syntax – **


    ● CREATE DATABASE _databasename_; 


    **<span style="text-decoration:underline;">DROP DATABASE:</span> **


    The DROP DATABASE statement is used to drop an existing SQL database. **Syntax – **


    ● DROP DATABASE _databasename_; 


    **<span style="text-decoration:underline;">CREATE TABLE:</span> **


    The CREATE TABLE statement is used to create a new table in a database.


    **Syntax – **


    ● CREATE TABLE _table_name _( 


         _column1 datatype_, 


         _column2 datatype_, 


         _column3 datatype_, 


         .... 


        ); 


    **<span style="text-decoration:underline;">DROP TABLE:</span> **


    The DROP TABLE statement is used to drop an existing table in a database. **Syntax – **


    ● DROP TABLE _table_name_; 


    **<span style="text-decoration:underline;">TRUNCATE TABLE:</span> **


    The TRUNCATE TABLE statement is used to delete the data inside a table, but not the table itself. **Syntax – **


    ● TRUNCATE TABLE _table_name_; 


    **<span style="text-decoration:underline;">ALTER TABLE:</span> **


    The ALTER TABLE statement is used to add, delete, or modify columns in an existing table. 


    The ALTER TABLE statement is also used to add and drop various constraints on an existing table. 


    **Syntax – **


    ● ALTER TABLE _table_name _


        ADD _column_name datatype_; 


    ● ALTER TABLE _table_name _


        DROP COLUMN _column_name_; 


    ● ALTER TABLE _table_name _


        MODIFY COLUMN _column_name datatype_; 


    **Ex – **


    ● ALTER TABLE Customers 


        ADD Email varchar(255);


    ● ALTER TABLE Customers 


        DROP COLUMN Email; 


    ● ALTER TABLE Persons 


        ALTER COLUMN DateOfBirth year;
