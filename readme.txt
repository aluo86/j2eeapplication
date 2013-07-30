1. Error: SEVERE: Error configuring application listener of class org.springframework.web.context.request.RequestContextListener
   Solution: 

1) Open the project's properties (e.g., right-click on the project's name in the project explorer and select "Properties")
2) select "Deployment Assembly"
3) Click the "Add..." button on the right margin
4) Select "Java Build Path Entries" from the menu of Directive Type and click "Next"
5) Select "Maven Dependencies" from the Java Build Path Entries menu and click "Finish".

You should see "Maven Dependencies" added to the Web Deployment Assembly definition.

2. 