This is a simple Rails application with 2 pages:

1. First page is a form with an input, where a user can type a question to ask the Coach
2. After submitting the form, the user is redirected to another page where she/he will see her/his question and the coach answer.

The logic of the app is simple and includes the below scenarios:

1. If the message is I am going to work, the coach will answer Great!
2. If the message has a question mark ? at the end, the coach will answer Silly question, get dressed and go to work!.
3. Otherwise the coach will answer I don't care, get dressed and go to work!
