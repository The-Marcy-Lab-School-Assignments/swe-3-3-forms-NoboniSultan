# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: Accessibility

What is accessibility and why does it matter? Name at least two ways that labels make our form inputs more accessible?

**Your Answer:**
Accessibility means designing websites so that everyone can use them, including people with disabilities. It matters because not all users interact with websites the same way, and everyone should have equal access to information and features. Labels help by clearly describing what an input is for, and they allow screen readers to read the input purpose out loud. Labels also make inputs easier to click because clicking the label focuses the input.

## Question 2: The `name` vs `id` Attribute

`for`, `name` and `id` are attributes we put on form labels and inputs, but they serve different purposes. Explain what each attribute is used for.

**Your Answer:**
The `id` attribute uniquely identifies an element on the page and is often used to connect a label to an input using the `for` attribute. The `for` attribute on a label matches the input's `id` so they are linked. The `name` attribute is used when the form is submitted, because it tells the server which piece of data is which. Without `name`, the input's value would not be sent.

## Question 3: Input Types

Why do we use specific input types like `type="email"` or `type="number"` instead of just using `type="text"` for everything? What advantages do they provide?

**Your Answer:**
We use specific input types like `email` or `number` because they help browsers understand what kind of data is expected. These types can automatically validate user input and prevent incorrect data. They also improve user experience, especially on mobile, by showing the correct keyboard. This makes forms faster and easier to use.
## Question 4: Form Submission

Form data is typically sent to a server (a computer that receives the data and does something with it). Provide an example of a real web application that uses a form and, to the best of your ability, explain what the application does with that form data.

**Your Answer:**
An example of a real web application that uses a form is a login page, like on Google or Instagram. The user enters their `username` and `password` into a form. When the form is submitted, the data is sent to the server to check if the information matches an existing account. If it matches, the user is logged in, if not, an error message is shown. 