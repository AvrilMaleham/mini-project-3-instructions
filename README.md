# Next.js Web App

For your third and final mini project, you will be converting the pizza website into Next.js!

## You will need to think about:

- Continue the good Git practices you have been using. Include a ReadMe, make use of branching, create meaningful commit messages, push to remote regularly, and don’t forget Git ignore.
- For this project, we will still be using dummy data, so no need to create a database just yet.
- Use the Bootstrap library for your components and notice how much smaller your CSS file becomes!
- Use the Next.js API folder to create your endpoints. Start with a GET endpoint; all other endpoints are <b>optional</b>. Make use of `NextRequest` from next server and `Response` to get the new pizza orders. Don’t forget to export it using the name `GET`.
- Map over lists to keep your code clean and concise; this will be particularly useful with your nav menu items and the menu of pizzas.
- You will need to pass props between your components.
- Use a mixture of Server Side Rendering and Client Side Rendering.

### SSR
SSR will ensure faster loading of the pizza site for customers and will enable better Search Engine Optimisation for our pizza site. The “orders” page will be SSR. Try adding a child of this server component that is a client component.

### CSR
We need this for the interactive components. In this project, the “home” page will be CSR as the key component is to search/filter the pizzas.

For the search/filter component, use React state management to create a component which users can apply search or filter to the pizza menu options.

![image](https://github.com/user-attachments/assets/6804e8ca-35b5-4871-9dea-11b54db0a020)

## Optional

Only if you would like to have a play with NextAuth. Our “orders” page can become an admin-only page, which requires a log in so that only authenticated users can view it. Refer to the class example: [first-next-app](https://github.com/dasingh9/first-next-app)

<img width="1442" alt="image" src="https://github.com/user-attachments/assets/b85bc25e-d534-462a-adee-01fdd112399d">

## Deadline

The deadline is 17/08. As always, let us know if you need any help or guidance. You will each be presenting your mini project to the class on 17/08.
