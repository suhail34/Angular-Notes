# COMPONENTS

Components are the main building block for Angular applications. Each component consists of:
1. An HTML template that declares what renders on the page
2. A TypeScript class that defines behavior
3. A CSS selector that defines how the component is used in a template
4. Optionally, CSS styles applied to the template

## Two ways to create angular component : 
1. Using Angular CLI.
2. Manually creating components.

### A. To create a component using the Angular CLI:
1. From a terminal window, navigate to the directory containing your application.
2. Run the ng generate component <component-name> command, where <component-name> is the name of your new component.

### B. To create component manually :
1. Navigate to your Angular project directory.
2. Create a new file, <component-name>.component.ts.
3. At the top of the file, add the following import statement.
4. After the import statement, add a @Component decorator.
5. Choose a CSS selector for the component.
6. Define the HTML template that the component uses to display information. In most cases, this template is a separate HTML file.
7. Select the styles for the component's template. In most cases, you define the styles for your component's template in a separate file.
8. Add a class statement that includes the code for the component.
