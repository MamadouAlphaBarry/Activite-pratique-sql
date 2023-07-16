# Activite-pratique-sql
<h2>CREATION DE LA BASE DE DONNEES</h2>
<img src="TABLE_DEP.PNG" alt="DATABASE" >
<h3>Tables Employe</h3>
<img src="table_employes.PNG" alt="DATABASE" >
<h3>Tables Employe</h3>
<img src="TABLE_DEP.PNG" alt="DATABASE" >
<h3> Employe Data</h3>
<img src="emp_data.PNG" alt="DATABASE" >
<h3> Departement Data</h3>
<img src="dep_data.PNG" alt="DATABASE" >
<h2>Ecrire des requêtes SQL pour accomplir les tâches suivantes</h2>
<h4>Sélectionnez toutes les données des employés. </h4>
 <pre> SELECT   * FROM employes; </pre>
<img src="tousLesEmployes.PNG" alt="DATABASE" >
 <pre> SELECT employes.NOM,departements.NOM FROM `employes` JOIN departements;</pre>
<img src="EMP_DEP.PNG" alt="DATABASE" >
<h3> Sélectionnez les noms des employés qui travaillent dans le département "
Informatique".</h3>
 <pre>SELECT employes.NOM,departements.NOM from employes JOIN departements WHERE departements.NOM="Informatique";</pre>
<img src="emp_informatique.PNG" alt="DATABASE" >
<h3> Sélectionnez les noms des employés qui travaillent dans le département "
Informatique".</h3>
 <pre>SELECT employes.NOM,departements.NOM from employes JOIN departements WHERE departements.NOM=null;</pre>




