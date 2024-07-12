# Essential papers for database developers

## Basics

### Essentials

* A relational model of data for large shared data banks (1970) - Codd, Edgar F. [https://dl.acm.org/doi/pdf/10.1145/362384.362685](https://dl.acm.org/doi/pdf/10.1145/362384.362685)
* SEQUEL: A structured English query language (1974) - Chamberlin, Donald D., and Raymond F. Boyce. [https://dl.acm.org/doi/pdf/10.1145/800296.811515](https://dl.acm.org/doi/pdf/10.1145/800296.811515)
* INGRES: a relational data base system (1975) - Held, G. D., M. R. Stonebraker, and Eugene Wong. [https://dl.acm.org/doi/pdf/10.1145/1499949.1500029](https://dl.acm.org/doi/pdf/10.1145/1499949.1500029)
* Extending the database relational model to capture more meaning (1979) - Codd, Edgar F. [https://dl.acm.org/doi/pdf/10.1145/320107.320109](https://dl.acm.org/doi/pdf/10.1145/320107.320109)
* A critique of the SQL database language (1984) - Date, C. J. [https://dl.acm.org/doi/pdf/10.1145/984549.984551](https://dl.acm.org/doi/pdf/10.1145/984549.984551)

### Consensus

* The Part-Time Parliament (1998) - Lamport, Leslie. [https://dl.acm.org/doi/pdf/10.1145/3335772.3335939](https://dl.acm.org/doi/pdf/10.1145/3335772.3335939)
* Paxos Made Simple (2001) - Lamport, Leslie. [https://www.microsoft.com/en-us/research/publication/2016/12/paxos-simple-Copy.pdf](https://www.microsoft.com/en-us/research/publication/2016/12/paxos-simple-Copy.pdf)
* Consensus: Bridging theory and practice (2014) - Ongaro, Diego. [https://web.stanford.edu/~ouster/cgi-bin/papers/OngaroPhD.pdf](https://web.stanford.edu/~ouster/cgi-bin/papers/OngaroPhD.pdf)
* In search of an understandable consensus algorithm (extended version) (2014) - Ongaro, Diego, and John Ousterhout. [https://www.repository.cam.ac.uk/bitstream/handle/1810/291682/thesis.pdf?sequence=1](https://www.repository.cam.ac.uk/bitstream/handle/1810/291682/thesis.pdf?sequence=1)
* Distributed consensus revised (2019) - Howard, Heidi. [https://www.repository.cam.ac.uk/bitstream/handle/1810/291682/thesis.pdf?sequence=1](https://www.repository.cam.ac.uk/bitstream/handle/1810/291682/thesis.pdf?sequence=1)
* A Generalised Solution to Distributed Consensus (2019) - Howard, Heidi, and Richard Mortier. [https://arxiv.org/pdf/1902.06776](https://arxiv.org/pdf/1902.06776)
* Paxos vs Raft: Have we reached consensus on distributed consensus? (2020) - Howard, Heidi, and Richard Mortier. [https://dl.acm.org/doi/pdf/10.1145/3380787.3393681](https://dl.acm.org/doi/pdf/10.1145/3380787.3393681)

### Consistency

* Consistency Tradeoffs in Modern Distributed Database System Design (2012) - Abadi, Daniel. [https://www.cs.umd.edu/~abadi/papers/abadi-pacelc.pdf](https://www.cs.umd.edu/~abadi/papers/abadi-pacelc.pdf)
* Logical physical clocks and consistent snapshots in globally distributed databases (2014) - Kulkarni S S, Demirbas M, Madappa D, et al. [https://cse.buffalo.edu/tech-reports/2014-04.pdf](https://cse.buffalo.edu/tech-reports/2014-04.pdf)
* Ark: A Real-World Consensus Implementation (2014) - Kasheff, Zardosht, and Leif Walsh. [https://arxiv.org/pdf/1407.4765](https://arxiv.org/pdf/1407.4765)
* PolarFS: an ultra-low latency and failure resilient distributed file system for shared storage cloud database (2018) - Cao, Wei, et al. [https://dl.acm.org/doi/pdf/10.14778/3229863.3229872](https://dl.acm.org/doi/pdf/10.14778/3229863.3229872)
* Anna: A kvs for any scale (2018) - Wu, Chenggang, et al. [https://www2.eecs.berkeley.edu/Pubs/TechRpts/2019/EECS-2019-122.pdf](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2019/EECS-2019-122.pdf)
* Strong and efficient consistency with consistency-aware durability (2021) - Ganesan, Aishwarya, et al. [https://dl.acm.org/doi/pdf/10.1145/3423138](https://dl.acm.org/doi/pdf/10.1145/3423138)

## System Design

### RDBMS

* System R: Relational Approach to Database Management (1976) - Astrahan, Morton M., et al. [https://dl.acm.org/doi/pdf/10.1145/320455.320457](https://dl.acm.org/doi/pdf/10.1145/320455.320457)
* The design and implementation of INGRES (1976) - Stonebraker, Michael, et al. [https://dl.acm.org/doi/10.1145/320473.320476](https://dl.acm.org/doi/10.1145/320473.320476)
* The design of Postgres (1986) - Stonebraker, Michael, and Lawrence A. Rowe. [https://dl.acm.org/doi/pdf/10.1145/16856.16888](https://dl.acm.org/doi/pdf/10.1145/16856.16888)
* Query Processing in Main Memory Database Management Systems (1986) - Lehman, Tobin J., and Michael J. Carey. [https://dl.acm.org/doi/pdf/10.1145/16894.16878](https://dl.acm.org/doi/pdf/10.1145/16894.16878)
* Megastore: Providing Scalable, Highly Available Storage for Interactive Services (2011) - Baker J, Bond C, Corbett J C, et al. [http://pages.cs.wisc.edu/~akella/CS838/F12/838-CloudPapers/Megastore.pdf](http://pages.cs.wisc.edu/~akella/CS838/F12/838-CloudPapers/Megastore.pdf)
* Spanner: Google's globally distributed database (2013) - Corbett, James C., et al. [https://dl.acm.org/doi/pdf/10.1145/2491245](https://dl.acm.org/doi/pdf/10.1145/2491245)
* Online, Asynchronous Schema Change in F1 (2013) - Rae, Ian, et al. [https://dl.acm.org/doi/pdf/10.14778/2536222.2536230](https://dl.acm.org/doi/pdf/10.14778/2536222.2536230)
* Amazon aurora: Design considerations for high throughput cloud-native relational databases (2017) - Verbitski, Alexandre, et al. [https://dl.acm.org/doi/pdf/10.1145/3035918.3056101](https://dl.acm.org/doi/pdf/10.1145/3035918.3056101)
* Looking Back at Postgres (2019) - Hellerstein, Joseph M. [https://arxiv.org/pdf/1901.01973](https://arxiv.org/pdf/1901.01973)
* CockroachDB: The Resilient Geo-Distributed SQL Database (2020) - Taft, Rebecca, et al. [https://dl.acm.org/doi/pdf/10.1145/3318464.3386134](https://dl.acm.org/doi/pdf/10.1145/3318464.3386134)
* F1 Lightning: HTAP as a Service (2020) - Yang, Jiacheng, et al. [https://dl.acm.org/doi/pdf/10.14778/3415478.3415553](https://dl.acm.org/doi/pdf/10.14778/3415478.3415553)
* TiDB: a Raft-based HTAP database (2020) - Huang, Dongxu, et al. [https://dl.acm.org/doi/pdf/10.14778/3415478.3415535](https://dl.acm.org/doi/pdf/10.14778/3415478.3415535)
* PolarDB Serverless: A Cloud Native Database for Disaggregated Data Centers (2021) - Cao, Wei, et al. [https://dl.acm.org/doi/pdf/10.1145/3448016.3457560](https://dl.acm.org/doi/pdf/10.1145/3448016.3457560)

### NoSQL

* Bigtable: A Distributed Storage System for Structured Data (2006) - Chang, Fay, et al. [https://dl.acm.org/doi/pdf/10.1145/1365815.1365816](https://dl.acm.org/doi/pdf/10.1145/1365815.1365816)
* Dynamo: Amazon’s Highly Available Key-value Store (2007) - DeCandia, Giuseppe, et al. [https://dl.acm.org/doi/pdf/10.1145/1323293.1294281](https://dl.acm.org/doi/pdf/10.1145/1323293.1294281)
* PNUTS: Yahoo!’s Hosted Data Serving Platform (2008) - Cooper, Brian F., et al. [https://dl.acm.org/doi/pdf/10.14778/1454159.1454167](https://dl.acm.org/doi/pdf/10.14778/1454159.1454167)
* Cassandra - A Decentralized Structured Storage System (2010) - Lakshman, Avinash, and Prashant Malik. [https://dl.acm.org/doi/pdf/10.1145/1773912.1773922](https://dl.acm.org/doi/pdf/10.1145/1773912.1773922)
* Windows azure storage: a highly available cloud storage service with strong consistency (2011) - Calder, Brad, et al. [https://dl.acm.org/doi/pdf/10.1145/2043556.2043571](https://dl.acm.org/doi/pdf/10.1145/2043556.2043571)
* Azure data lake store: a hyperscale distributed file service for big data analytics (2017) - Ramakrishnan, Raghu, et al. [https://dl.acm.org/doi/pdf/10.1145/3035918.3056100](https://dl.acm.org/doi/pdf/10.1145/3035918.3056100)
* PNUTS to Sherpa: Lessons from Yahoo!’s Cloud Database (2019) - Cooper, Brian F., et al. [https://dl.acm.org/doi/pdf/10.14778/3352063.3352146](https://dl.acm.org/doi/pdf/10.14778/3352063.3352146)

## SQL Engine

### Optimizer Framework

* Access Path Selection in a Relational Database Management System (1979) - Selinger, P. Griffiths, et al. [https://dl.acm.org/doi/pdf/10.1145/582095.582099](https://dl.acm.org/doi/pdf/10.1145/582095.582099)
* Query Optimization by Simulated Annealing (1987) - Ioannidis, Yannis E., and Eugene Wong. [https://dl.acm.org/doi/pdf/10.1145/38713.38722](https://dl.acm.org/doi/pdf/10.1145/38713.38722)
* The EXODUS Optimizer Generator (1987) - Graefe, Goetz, and David J. DeWitt. [https://dl.acm.org/doi/pdf/10.1145/38713.38734](https://dl.acm.org/doi/pdf/10.1145/38713.38734)
* Extensible/Rule Based Query Rewrite Optimization in Starburst (1992) - Pirahesh, Hamid, Joseph M. Hellerstein, and Waqar Hasan. [https://dl.acm.org/doi/pdf/10.1145/141484.130294](https://dl.acm.org/doi/pdf/10.1145/141484.130294)
* The Volcano Optimizer Generator- Extensibility and Efficient Search (1993) - Graefe, Goetz, and William J. McKenna. [https://www.cse.iitb.ac.in/infolab/Data/Courses/CS632/Papers/Volcano-graefe.pdf](https://www.cse.iitb.ac.in/infolab/Data/Courses/CS632/Papers/Volcano-graefe.pdf)
* The Cascades Framework for Query Optimization (1995) - Graefe, Goetz. [https://liuyehcf.github.io/resources/paper/The-Cascades-Framework-For-Query-Optimization.pdf](https://liuyehcf.github.io/resources/paper/The-Cascades-Framework-For-Query-Optimization.pdf)
* An Overview of Query Optimization in Relational Systems (1998) - Chaudhuri, Surajit. [https://dl.acm.org/doi/pdf/10.1145/1007568.1007642](https://dl.acm.org/doi/pdf/10.1145/1007568.1007642)
* Robust Query Processing through Progressive Optimization (2004) - Markl, Volker, et al. [https://dl.acm.org/doi/pdf/10.1145/1007568.1007642](https://dl.acm.org/doi/pdf/10.1145/1007568.1007642)
* Orca: A Modular Query Optimizer Architecture for Big Data (2014) - Soliman, Mohamed A., et al. [https://dl.acm.org/doi/pdf/10.1145/2588555.2595637](https://dl.acm.org/doi/pdf/10.1145/2588555.2595637)
* Parallelizing Query Optimization on Shared-Nothing Architectures (2015) - Trummer, Immanuel, and Christoph Koch. [https://arxiv.org/pdf/1511.01768](https://arxiv.org/pdf/1511.01768)
* The MemSQL Query Optimizer: A modern optimizer for real-time analytics in a distributed database (2016) - Chen, Jack, et al. [https://dl.acm.org/doi/pdf/10.14778/3007263.3007277](https://dl.acm.org/doi/pdf/10.14778/3007263.3007277)

### Transformation

* Processing queries with quantifiers a horticultural approach (1983) - Dayal, Umeshwar.
（https://dl.acm.org/doi/pdf/10.1145/588058.588075）
* Translating SQL into relational algebra: Optimization, semantics, and equivalence of SQL queries (1985) - Ceri, Stefano, and Georg Gottlob.
（https://www.academia.edu/download/50687636/tse.1985.23222320161202-29901-8u86ef.pdf）
* Grammar-like Functional Rules for Representing Query Optimization Alternatives, (1988) - Lohman, Guy M.
（https://dl.acm.org/doi/pdf/10.1145/971701.50204）
* Query Optimization by Predicate Move-Around (1994) - Levy, Alon Y., Inderpal Singh Mumick, and Yehoshua Sagiv.
（https://www.researchgate.net/profile/Inderpal-Mumick/publication/2754592_Query_Optimization_by_Predicate_Move-Around/links/0f317534d437e49755000000/Query-Optimization-by-Predicate-Move-Around.pdf）
* Eager Aggregation and Lazy Aggregation (1995) - Yan, Weipeng P., and Per-Bike Larson.
（https://www.researchgate.net/profile/Per-Ake-Larson/publication/2733082_Eager_Aggregation_and_Lazy_Aggregation/links/02bfe50ce6de3dad7c000000/Eager-Aggregation-and-Lazy-Aggregation.pdf）
* Parameterized Queries and Nesting Equivalences (2000) - Galindo-Legaria, C. A.
（https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-2000-31.pdf）
* Cost-based query transformation in Oracle (2006) - Ahmed, Rafi, et al.
（https://www.researchgate.net/profile/Rafi-Ahmed-2/publication/221311318_Cost-Based_Query_Transformation_in_Oracle/links/572bbc5e08aef7c7e2c6b829/Cost-Based-Query-Transformation-in-Oracle.pdf）

### Nested Query

* Using semi-joins to solve relational queries (1981) - Bernstein, Philip A., and Dah-Ming W. Chiu.
（https://dl.acm.org/doi/pdf/10.1145/322234.322238）
* On optimizing an SQL-like nested query (1982) - Kim, Won.
（https://dl.acm.org/doi/pdf/10.1145/319732.319745）
* Optimization of nested queries in a distributed relational database (1984) - L&man, Guy M., et al.
（https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=12fd1fe22687f5944613832de4e64ef902043aec）
* SQL-like and Quel-like correlation queries with aggregates revisited (1984) - Kiessling, Werner.
（http://www2.eecs.berkeley.edu/Pubs/TechRpts/1984/ERL-m-84-75.pdf）
* Translating SQL into relational algebra: Optimization, semantics, and equivalence of SQL queries (1985) - Ceri, Stefano, and Georg Gottlob.
（https://www.academia.edu/download/50687636/tse.1985.23222320161202-29901-8u86ef.pdf）
* Optimization of nested SQL queries revisited (1987) - Ganski, Richard A., and Harry KT Wong.
（https://dl.acm.org/doi/pdf/10.1145/38714.38723）
* A Unitied Approach to Processing Queries That Contain Nested Subqueries, Aggregates, and Quantifiers (1987) - Dayal, Umeshwar.
（https://vldb.org/conf/1987/P197.PDF）
* Optimization of correlated SQL queries in a relational database management system (1998) - Jou, Michelle M., Ting Yu Leung, and Mir Hamid Pirahesh.
（https://patentimages.storage.googleapis.com/3b/24/39/a947424a6eb0ea/US5822750.pdf）
* Orthogonal Optimization of Subqueries and Aggregation (2001) - Galindo-Legaria, César, and Milind Joshi.
（https://dl.acm.org/doi/pdf/10.1145/376284.375748）
* WinMagic : Subquery Elimination Using Window Aggregation (2003) - Zuzarte, Calisto, et al.
（https://dl.acm.org/doi/pdf/10.1145/872757.872840）
* Execution strategies for SQL subqueries (2007) - Elhemali, Mostafa, et al.
（https://dl.acm.org/doi/pdf/10.1145/1247480.1247598）
* Enhanced subquery optimizations in Oracle (2009) - Bellamkonda, Srikanth, et al.
（https://dl.acm.org/doi/pdf/10.14778/1687553.1687563）
* Unnesting Arbitrary Queries) (2015) - Neumann, Thomas, and Alfons Kemper.
（https://dl.gi.de/bitstream/handle/20.500.12116/2418/383.pdf?sequence=1）

### Functional Dependencies

* Fundamental Techniques for Order Optimization (1996) - Simmen, David, Eugene Shekita, and Timothy Malkemus.
（https://dl.acm.org/doi/pdf/10.1145/233269.233320）
* [Thesis] Exploiting Functional Dependence in Query Optimization (2000) - Paulley, Glenn Norman.
（https://cs.uwaterloo.ca/research/tr/2000/11/CS-2000-11.thesis.pdf）
* An Efficient Framework for Order Optimization (2004) - Neumann, Thomas, and Guido Moerkotte.
（https://madoc.bib.uni-mannheim.de/736/1/TR-03-011.pdf）
* Incorporating Partitioning and Parallel Plans into the SCOPE Optimizer (2010) - Zhou, Jingren, Per-Ake Larson, and Ronnie Chaiken.
（http://www.cs.albany.edu/~jhh/courses/readings/zhou10.pdf）
* Accelerating Queries with GroupBy and Join by Group join (2011) - Moerkotte, Guido, and Thomas Neumann.
（https://dl.acm.org/doi/pdf/10.14778/3402707.3402723）

### Join Order

* Access paths in the" Abe" statistical query facility (1982) - Klug, Anthony.
（https://dl.acm.org/doi/pdf/10.1145/582353.582382）
* Extending the Algebraic Framework of Query Processing to Handle Outerjoins (1984) - RosenthaI, A., and D. Reiner.
（https://www.vldb.org/conf/1984/P334.PDF）
* Analysis of Two Existing and One New Dynamic Programming Algorithm for the Generation of Optimal Bushy Join Trees without Cross Products (2006) - Moerkotte, Guido, and Thomas Neumann.
（https://www.researchgate.net/profile/Thomas_Neumann2/publication/47861835_Analysis_of_Two_Existing_and_One_New_Dynamic_Programming_Algorithm_for_the_Generation_of_Optimal_Bushy_Join_Trees_without_Cross_Products/links/0912f506d90ad19031000000.pdff）
* Dynamic programming strikes back (2008) - Moerkotte, Guido, and Thomas Neumann.
（https://dl.acm.org/doi/pdf/10.1145/1376616.1376672）
* On the Correct and Complete Enumeration of the Core Search Space (2013) - Moerkotte, Guido, Pit Fender, and Marius Eich.
（https://dl.acm.org/doi/pdf/10.1145/2463676.2465314）
* How Good Are Query Optimizers, Really? (2015) - Leis, Viktor, et al.
（https://dl.acm.org/doi/pdf/10.14778/2850583.2850594）
* The Complete Story of Joins (2017) - Neumann, Thomas, Viktor Leis, and Alfons Kemper.
（https://dl.gi.de/bitstreams/535a5d94-043d-4b1a-9062-fbaf8ed35468/download）
* Improving Join Reorderability with Compensation Operators (2018) - Wang, TaiNing, and Chee-Yong Chan.
（https://dl.acm.org/doi/pdf/10.1145/3183713.3183731）
* Adaptive Optimization of Very Large Join Queries (2018) - Neumann, Thomas, and Bernhard Radke.
（https://dl.acm.org/doi/pdf/10.1145/3183713.3183733）

### Cost Model

* Modelling Costs for a MM-DBMS (1996) - Listgarten, Sherry, and Marie-Anne Neimat.
（https://www.semanticscholar.org/paper/Modelling-Costs-for-a-MM-DBMS-Listgarten-Neimat/42b88445cfb28fbe4b6539c97674a8fa9815e635）
* SEEKing the truth about ad hoc join costs (1997) - Haas, Laura M., et al.
（https://minds.wisconsin.edu/bitstream/handle/1793/59726/TR1148.pdf?sequence=11）
* Approximation Schemes for Many-Objective Query Optimization (2014) - Trummer, Immanuel, and Christoph Koch.
（https://dl.acm.org/doi/pdf/10.1145/2588555.2610527）
* Multi-Objective Parametric Query Optimization (2015) - Trummer, Immanuel, and Christoph Koch.
（https://dl.acm.org/doi/pdf/10.1145/3068612）

### Statistics

* Accurate Estimation of the Number of Tuples Satisfying a Condition (1984) - Piatetsky-Shapiro, Gregory, and Charles Connell.
（https://dl.acm.org/doi/pdf/10.1145/971697.602294）
* Optimal Histograms for Limiting Worst-Case Error Propagation in the Size of Join Results (1993) - Ioannidis, Yannis E., and Stavros Christodoulakis.
（https://dl.acm.org/doi/pdf/10.1145/169725.169708）
* Universality of Serial Histograms (1993) - Ioannidis, Yannis E.
（https://vldb.org/conf/1993/P256.PDF）
* Balancing Histogram Optimality and Practicality for Query Result Size Estimation (1995) - Ioannidis, Yannis E., and Viswanath Poosala.
（https://dl.acm.org/doi/pdf/10.1145/568271.223841）
* Improved Histograms for Selectivity Estimation of Range Predicates (1996) - Poosala, Viswanath, et al.
（https://dl.acm.org/doi/pdf/10.1145/235968.233342）
* The History of Histograms (2003) - Ioannidis, Yannis.
（http://www.vldb.org/conf/2003/papers/S02P01.pdf）
* Automated Statistics Collection in DB2 UDB (2004) - Aboulnaga, Ashraf, et al.
（http://www.vldb.org/conf/2004/IND5P3.PDF）
* Adaptive Query Processing in the Looking Glass (2005) - Babu, Shivnath, and Pedro Bizarro.
（https://eden.dei.uc.pt/~bizarro/papers/cidr2005_aqp.pdf）
* Optimizer plan change management: improved stability and performance in Oracle 11g (2008) - Ziauddin, Mohamed, et al.
（https://dl.acm.org/doi/pdf/10.14778/1454159.1454175）
* Histograms Reloaded: The Merits of Bucket Diversity (2010) - Kanne, Carl-Christian, and Guido Moerkotte.
（https://dl.acm.org/doi/pdf/10.1145/1807167.1807239）
* Synopses for Massive Data: Samples, Histograms, Wavelets, Sketches (2011) - Cormode, Graham, et al.
（https://www.nowpublishers.com/article/DownloadSummary/DBS-004）
* Exploiting Ordered Dictionaries to Efficiently Construct Histograms with Q-Error Guarantees in SAP HANA (2014) - Moerkotte, Guido, et al.Adaptive Statistics in Oracle 12c (2017) - Chakkappen, Sunil, et al.
（https://dl.acm.org/doi/pdf/10.1145/2588555.2595629）
* Adaptive Statistics in Oracle 12c (2017) - Chakkappen, Sunil, et al.
（https://dl.acm.org/doi/pdf/10.14778/3137765.3137785）

### Probabilistic Counting

* Towards Estimation Error Guarantees for Distinct Values (2000) - Charikar, Moses, et al.
（https://dl.acm.org/doi/pdf/10.1145/335168.335230）
* Distinct Sampling for Highly-Accurate Answers to Distinct Values Queries and Event Reports (2001) - Gibbons, Phillip B.
（http://www.vldb.org/conf/2001/P541.pdf）
* LEO – DB2’s LEarning Optimizer (2001) - Stillger, Michael, et al.
（http://www.vldb.org/conf/2001/P019.pdf）
* An Improved Data Stream Summary: The Count-Min Sketch and its Applications, Journal of Algorithms (2005) - Cormode, Graham, and Shan Muthukrishnan.
（http://twiki.di.uniroma1.it/pub/Ing_algo/WebHome/p14_Cormode_JAl_05.pdf）
* New Estimation Algorithms for Streaming Data: Count-min Can Do More (2007) - Deng, Fan, and Davood Rafiei.
（https://www.academia.edu/download/31052190/cmm.pdf）
* Preventing Bad Plans by Bounding the Impact of Cardinality Estimation Errors (2009) - Moerkotte, Guido, Thomas Neumann, and Gabriele Steidl.
（https://dl.acm.org/doi/pdf/10.14778/1687627.1687738）
* Pessimistic Cardinality Estimation: Tighter Upper Bounds for Intermediate Join Cardinalities (2019) - Cai, Walter, Magdalena Balazinska, and Dan Suciu.
（https://dl.acm.org/doi/pdf/10.1145/3299869.3319894）
* Deep Unsupervised Cardinality Estimation (2019) - Yang, Zongheng, et al.
（https://arxiv.org/pdf/1905.04278）
* NeuroCard: One Cardinality Estimator for All Tables (2020) - Yang, Zongheng, et al.
（https://arxiv.org/pdf/2006.08109）

### Execution Engine

* QueryEvaluationTechniquesfor LargeDatabas (1993) - Graefe G.
（https://dl.acm.org/doi/pdf/10.1145/152610.152611）
* Volcano - An Extensible and Parallel Query Evaluation System (1994) - Graefe, Goetz.
（https://15721.courses.cs.cmu.edu/spring2016/papers/graefe-ieee1994.pdf）
* MonetDB/X100: Hyper-Pipelining Query Execution (2005) - Boncz, Peter A., Marcin Zukowski, and Niels Nes.
（https://www.researchgate.net/profile/Niels-Nes/publication/45338800_MonetDBX100_Hyper-Pipelining_Query_Execution/links/0deec520cd1e8a3607000000/MonetDB-X100-Hyper-Pipelining-Query-Execution.pdf）
* Efficiently Compiling Efficient Query Plans for Modern Hardware (2011) - Neumann, Thomas.
（https://dl.acm.org/doi/pdf/10.14778/2002938.2002940）
* Multi-Core, Main-Memory Joins: Sort vs. Hash Revisited (2013) - Balkesen, Cagri, et al.
（https://dl.acm.org/doi/pdf/10.14778/2732219.2732227）
* Morsel-Driven Parallelism: A NUMA-Aware Query Evaluation Framework for the Many-Core Age (2014) - Leis, Viktor, et al.
（https://dl.acm.org/doi/pdf/10.1145/2588555.2610507）
* Relaxed Operator Fusion for In-Memory Databases: Making Compilation, Vectorization, and Prefetching Work Together At Last (2017) - Menon, Prashanth, Todd C. Mowry, and Andrew Pavlo.
（https://dl.acm.org/doi/pdf/10.14778/3151113.3151114）
* Looking Ahead Makes Query Plans Robust (2017) - Zhu, Jianqiao, et al.
（https://dl.acm.org/doi/pdf/10.14778/3090163.3090167）
* Everything You Always Wanted to Know About Compiled and Vectorized Queries But Were Afraid to Ask (2018) - Kersten, Timo, et al.
（https://dl.acm.org/doi/pdf/10.14778/3275366.3284966）
* SuRF: Practical Range Query Filtering with Fast Succinct Tries (2018) - Zhang, Huanchen, et al.
（https://dl.acm.org/doi/pdf/10.1145/3183713.3196931）
* Adaptive Execution of Compiled Queries (2018) - Kohn, André, Viktor Leis, and Thomas Neumann.
（https://15721.courses.cs.cmu.edu/spring2019/papers/19-compilation/kohn-icde2018.pdff）

### MPP Optimizations

* DB2 Parallel Edition (1995) - Baru, Chaitanya K., et al.
（https://grape.ics.uci.edu/wiki/asterix/raw-attachment/wiki/cs295-2009-fall/ParallelDB2.pdf）
* Parallel SQL execution in Oracle 10g (2004) - Cruanes, Thierry, Benoit Dageville, and Bhaskar Ghosh.
（https://dl.acm.org/doi/pdf/10.1145/1007568.1007666）
* Query Optimization in Microsoft SQL Server PDW (2012) - Shankar, Srinath, et al.
（https://dl.acm.org/doi/pdf/10.1145/2213836.2213953）
* Adaptive and big data scale parallel execution in Oracle (2013) - Bellamkonda, Srikanth, et al.
（https://dl.acm.org/doi/pdf/10.14778/2536222.2536235）
* Optimizing Queries over Partitioned Tables in MPP Systems (2014) - Antova, Lyublena, et al.
（https://dl.acm.org/doi/pdf/10.1145/2588555.2595640）

## Storage Engine

### Storage Structure

* The Ubiquitous B-Tree (1979) - Comer, Douglas.
（https://dl.acm.org/doi/pdf/10.1145/356770.356776）
* The 5 Minute Rule for Trading Memory for Disc Accesses and the 5 Byte Rule for Trading Memory for CPU Time (1987) - Gray, Jim, and Franco Putzolu.
（https://dl.acm.org/doi/pdf/10.1145/38713.38755）
* The Log-Structured Merge-Tree (LSM-Tree) (1996) - O’Neil, Patrick, et al.
（https://www.inf.ufpr.br/eduardo/ensino/ci763/papers/lsmtree.pdf）
* The five-minute rule ten years later, and other computer storage rules of thumb (1997) - Gray, Jim, and Goetz Graefe.
（https://dl.acm.org/doi/pdf/10.1145/271074.271094）
* The Five Minute Rule 20 Years Later and How Flash Memory Changes the Rules (2008) - Graefe, Goetz.
（https://dl.acm.org/doi/pdf/10.1145/1363189.1363198）
* A Comparison of Fractal Trees to Log-Structured Merge (LSM) Trees (2014) - Kuszmaul, Bradley C.
（http://www.pandademo.com/wp-content/uploads/2017/12/A-Comparison-of-Fractal-Trees-to-Log-Structured-Merge-LSM-Trees.pdf）
* Design Tradeoffs of Data Access Methods (2016) - Athanassoulis, Manos, and Stratos Idreos.
（https://dl.acm.org/doi/pdf/10.1145/2882903.2912569）
* Designing Access Methods: The RUM Conjecture (2016) - Athanassoulis, Manos, et al.
（https://stratos.seas.harvard.edu/sites/scholar.harvard.edu/files/stratos/files/rum.pdf）
* The five minute rule thirty years later and its impact on the storage hierarchy (2017) - Appuswamy, Raja, et al.
（https://infoscience.epfl.ch/record/230398/files/adms-talk.pdf）
* WiscKey: Separating Keys from Values in SSD-conscious Storage (2017) - Lu, Lanyue, et al.
（https://dl.acm.org/doi/pdf/10.1145/3033273）
* Managing Non-Volatile Memory in Database Systems (2018) - van Renen, Alexander, et al.
（https://dl.acm.org/doi/pdf/10.1145/3183713.3196897）
* LeanStore: In-Memory Data Management Beyond Main Memory (2018) - Leis, Viktor, et al.
（https://15721.courses.cs.cmu.edu/spring2020/papers/23-largethanmemory/leis-icde2018.pdf）
* The Case for Learned Index Structures (2018) - Kraska, Tim, et al.
（https://dl.acm.org/doi/pdf/10.1145/3183713.3196909）
* LSM-based Storage Techniques: A Survey (2019) - Luo, Chen, and Michael J. Carey.
（https://arxiv.org/pdf/1812.07527）
* Learning Multi-dimensional Indexes (2019) - Nathan, Vikram, et al.
（https://dl.acm.org/doi/pdf/10.1145/3318464.3380579）
* Umbra: A Disk-Based System with In-Memory Performance (2020) - Neumann, Thomas, and Michael J. Freitag.
（https://db.in.tum.de/~freitag/papers/p29-neumann-cidr20.pdf）
* XIndex: A Scalable Learned Index for Multicore Data Storage (2020) - Tang, Chuzhe, et al.
（https://dl.acm.org/doi/pdf/10.1145/3332466.3374547）
* The PGM-index: a fully-dynamic compressed learned index with provable worst-case bounds (2020) - Ferragina, Paolo, and Giorgio Vinciguerra.
（https://dl.acm.org/doi/pdf/10.14778/3389133.3389135）
* From WiscKey to Bourbon: A Learned Index for Log-Structured Merge Trees (2020) - Dai, Yifan, et al.
（https://www.usenix.org/system/files/osdi20-dai_0.pdf）
* CaaS-LSM: Compaction-as-a-Service for LSM-based Key-Value Stores in Storage Disaggregated Infrastructure (2024) - Yu, Qiaolin et al.
（https://qiaolin-yu.github.io/pubs/V2mod124-yu.pdf）

### Transaction

* The Notions of Consistency and Predicate Locks in a Database System (1976) - Eswaran, Kapali P., et al.
（https://dl.acm.org/doi/pdf/10.1145/360363.360369）
* Concurrency Control in Distributed Database Systems (1981) - Bernstein, Philip A., and Nathan Goodman.
（https://dl.acm.org/doi/pdf/10.1145/356842.356846）
* On Optimistic Methods for Concurrency Control (1981) - Kung, Hsiang-Tsung, and John T. Robinson.
（https://dl.acm.org/doi/pdf/10.1145/319566.319567）
* Principles of transaction-oriented database recovery (1983) - Haerder, Theo, and Andreas Reuter.
（https://dl.acm.org/doi/10.1145/289.291）
* Multiversion Concurrency Control - Theory and Algorithms (1983) - Bernstein, Philip A., and Nathan Goodman.
（https://dl.acm.org/doi/pdf/10.1145/319996.319998）
* ARIES: A transaction recovery method supporting fine-granularity locking and partial rollbacks using write-ahead logging (1992) - Mohan C, Haderle D, Lindsay B, et al.
（https://dl.acm.org/doi/pdf/10.1145/128765.128770）
* A Critique of ANSI SQL Isolation Levels (1995) - Berenson, Hal, et al.
（https://dl.acm.org/doi/pdf/10.1145/568271.223785）
* Generalized Isolation Level Definitions (2000) - Adya, Atul, Barbara Liskov, and Patrick O'Neil.
（https://pmg.csail.mit.edu/papers/icde00.pdf）
* Serializable Snapshot Isolation in PostgreSQL (2012) - Ports, Dan RK, and Kevin Grittner.
（https://arxiv.org/pdf/1208.4179.pdf,）
* Calvin: Fast Distributed Transactions for Partitioned Database Systems (2012) - Thomson, Alexander, et al.
（https://dl.acm.org/doi/pdf/10.1145/2213836.2213838）
* MaaT: effective and scalable coordination of distributed transactions in the cloud (2014) - Mahmoud, Hatem A., et al.
（https://dl.acm.org/doi/pdf/10.14778/2732269.2732270）
* Staring into the Abyss: An Evaluation of Concurrency Control with One Thousand Cores (2014) - Yu, Xiangyao, et al.
（https://dspace.mit.edu/bitstream/handle/1721.1/100022/Devadas_Staring%20into.pdf?sequence=1&isAllowed=y）
* An Evaluation of the Advantages and Disadvantages of Deterministic Database Systems (2014) - Ren, Kun, Alexander Thomson, and Daniel J. Abadi.
（https://dl.acm.org/doi/pdf/10.14778/2732951.2732955）
* Fast Serializable Multi-Version Concurrency Control for Main-Memory Database Systems (2015) - Neumann, Thomas, Tobias Mühlbauer, and Alfons Kemper.
（https://dl.acm.org/doi/pdf/10.1145/2723372.2749436）
* An Empirical Evaluation of In-Memory Multi-Version Concurrency Control (2017) - Wu, Yingjun, et al.
（https://dl.acm.org/doi/pdf/10.14778/3067421.3067427）
* An Evaluation of Distributed Concurrency Control (2017) - Harding, Rachael, et al.
（https://dl.acm.org/doi/pdf/10.14778/3055540.3055548）
* Scalable Garbage Collection for In-Memory MVCC Systems (2019) - Böttcher, Jan, et al.
（https://dl.acm.org/doi/pdf/10.14778/3364324.3364328）

### Scheduling

* Automated Demand-driven Resource Scaling in Relational Database-as-a-Service (2016) - Das, Sudipto, et al.
（https://dl.acm.org/doi/pdf/10.1145/2882903.2903733）
* Autoscaling Tiered Cloud Storage in Anna (2019) - Wu, Chenggang, Vikram Sreekanti, and Joseph M. Hellerstein.
（https://dl.acm.org/doi/pdf/10.14778/3311880.3311881）
* Adaptive HTAP through Elastic Resource Scheduling (2020) - Raza, Aunn, et al.
（https://dl.acm.org/doi/pdf/10.1145/3318464.3389783）
* MorphoSys: Automatic Physical Design Metamorphosis for Distributed Database Systems (2020) - Abebe, Michael, Brad Glasbergen, and Khuzaima Daudjee.
（https://dl.acm.org/doi/pdf/10.14778/3424573.3424578）

## Miscellaneous

### Workload

* TPC-H Analyzed: Hidden Messages and Lessons Learned from an Influential Benchmark (2013) - Boncz, Peter, Thomas Neumann, and Orri Erling.
（https://www.researchgate.net/profile/Peter-Boncz/publication/291257517_TPC-H_Analyzed_Hidden_Messages_and_Lessons_Learned_from_an_Influential_Benchmark/links/5852dbf708ae95fd8e1d749b/TPC-H-Analyzed-Hidden-Messages-and-Lessons-Learned-from-an-Influential-Benchmark.pdff）
* Quantifying TPCH Choke Points and Their Optimizations (2020) - Dreseler, Markus, et al.
（https://dl.acm.org/doi/pdf/10.14778/3389133.3389138）

### Network

* The End of Slow Networks: It's Time for a Redesign (2015) - Binnig, Carsten, et al.
（https://arxiv.org/pdf/1504.01048）
* Accelerating Relational Databases by Leveraging Remote Memory and RDMA (2016) - Li, Feng, et al.
（https://dl.acm.org/doi/pdf/10.1145/2882903.2882949）
* Don't Hold My Data Hostage: A Case for Client Protocol Redesign (2017) - Raasveldt, Mark, and Hannes Mühleisen.
（https://dl.acm.org/doi/pdf/10.14778/3115404.3115408）

### Quality

* Testing the Accuracy of Query Optimizers (2012) - Gu, Zhongxian, Mohamed A. Soliman, and Florian M.
（https://dl.acm.org/doi/pdf/10.1145/2304510.2304525）

### Diagnosis and Tuning

* Automatic SQL Tuning in Oracle 10g (2004) - Dageville B, Das D, Dias K, et al.
（http://www.vldb.org/conf/2004/IND4P2.PDF）
* Automatic Performance Diagnosis and Tuning in Oracle (2005) - Dias K, Ramacher M, Shaft U, et al.
（https://www.cidrdb.org/cidr2005/papers/P07.pdf）

