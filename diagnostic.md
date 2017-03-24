# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components. Explain why each piece might be it's own component.

    ```md
    The first thing that comes to mind is a social media profile. A component consists of two parts, a template that defines how it looks and a Javascript source file. The component manages how a user sees and interacts with the individual parts of their profile, so the profile is a component made up of attributes such as their profile picture and friend list.
    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
ember g component my-map
    ```

1.  What files are created and/or edited to produce a component, and what are their responsibilities?

    ```md
    We are given the component file itself, a template and a test.
    The integration test is to check certain behaviors of the attributes of the component.
    The template manages how users see and interact with the component.
    The component file itself gives values to the attributes.
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` route. What is
    the syntax (code that is written) to render this component inside that template?

    ```html
Sorry, I did not have time for this.
    ```

1.  Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
Sorry, I did not have time for this.
    ```
