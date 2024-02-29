<h2>Step 1 - Blazor App</h2>
This Blazor App forms step 1 of the Address Book tech test. 

Although you can run this app on it's own, functionality will be limited as it relies on a connection to a web api to perform the operations.

<h3>Companion Web API</h3>
This solution forms 1 of 2 parts. The other part is a Web Api that this Blazor app consumes.

To access the Web API solution, please got to this repo: [Web API - master branch](https://github.com/miketr33/AddressBookWebApi/tree/master) and clone the latest from the master branch. 

<h2>To run locally:</h2> 
1. Open both solutions in 2 instances of your IDE.
2. Run the Web Api solution (you will see the Swagger UI loaded when it is ready).
3. Run the Blazor app (another browser window will open and you will see a simple blazor web page.

Note: Validation has not yet been fully implemented so for both the Post and Put's you must ensure your json is valid before passing. In addition to the sample JSON, an Id field has been added. This will take any valid integer. 

If you experience any issues getting the two parts to communicate, you may need to adjust the port configurations in program.cs for each solution.

<em>All work completed by Mike Tree 2024</em>
