# DB_employees

The simple service - db of employees.

<ul>
 <li>configuration: xml</li>
 <li>DB: MySql</li>
 <li>Server: apache-tomcat-9.0.46</li>
 </ul>

<p>
Technologies
</p>
<ol>
 <li> Spring MVC</li>
 <li>Spring AOP</li>
 <li>Hibernate</li>
 <li>Jsp</li>
</ol>


MySql script:

<p>

USE my_db;<br>

CREATE TABLE employees (<br>
id int NOT NULL AUTO_INCREMENT,<br>
name varchar(15),<br>
surname varchar(25),<br>
department varchar(20),<br>
salary int,<br>
PRIMARY KEY (id)<br>
) ;

</p>




    