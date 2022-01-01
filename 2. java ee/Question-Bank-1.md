# Java EE Interview Questions
## Question Bank 1

1. <strong>Difference between jsp include action and derivative.</strong><br/>
    | JSP Inlcude Directive | JSP Include Action |
    | --------------------- | ------------------ |
    | Includes resource at translation time. | Includes resource at request time. |
    | Better for static pages. | Better for dynamic pages. |
    | Includes the original content in the generated servlet. | Calls the include method. |

2. <strong>Pass paramters from one jsp to another.</strong><br/>
    - Using query parameter
    - Using hidden variable
    - Using session object

3. <strong>What is the jsp usebean?</strong><br/>
    The jsp:useBean action tag is used to locate or instantiate a bean class. If bean object of the Bean class is already created, it doesn't create the bean depending on the scope. But if object of bean is not created, it instantiates the bean.