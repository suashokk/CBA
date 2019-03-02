

Handling property file and process it for bar chart rendering.
Hereby Abstracting the data(DAO) part by putting
it in property file for this assignment. 
Flow:::: Reading evolving data from property file.
We can customize rendering of evolving data.
If addition of any category or any penalties columns.
Abstracting Rendering using Jpanel object instead of View layer.

Execution flow.
1)Extract the file using password<CBA>
2)Import the project using existing project from Eclipse.
3)copy the application.properties file location in workspace and change the path in  EvolvingDataRenderingUtil.renderandcreateBarchart() under the below line 
input = new FileInputStream(
"C:\\Users\\user\\eclipse-workspace\\evolving.data.rendering.project
\\src\\com.cba.internal.evolving.data.rendering.properties\\application.properties");
4)Run App.java file as java application.
5)Evolving of data can be handled by code for year level and also argument an be customized. 




