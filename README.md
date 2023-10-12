# 3SC Web Developer Task - Cube Academy

This task is designed to assess how you will go about building a web application. You must demonstrate your ability to:

- Write readable, and well structured code
- Interpret and follow designs

## Brief

Build a cube of the month nomination frontend that integrates with an API.

You should attempt to follow the [designs](https://www.figma.com/file/j9opgFDjgfmgsIcTpkvyEt/FED-Mini-Task-Flow?type=design&mode=design&t=cvBjihTJPiiIVaGK-1).

The designs include:

- A design system (to help with creating a "theme" and re-usable elements).
- Desktop and Mobile layouts (please use both these to create the site in a responsive way).

The designs act as a source of truth for functional requirements.

Approach this task critically and come to the table with compromises, assumptions or questions when the picture isn't clear.

## Useful links

- Designs: [Figma](https://www.figma.com/file/j9opgFDjgfmgsIcTpkvyEt/FED-Mini-Task-Flow?type=design&mode=design&t=cvBjihTJPiiIVaGK-1)
- API documentation: [OpenAPI docs](https://cube-academy-api.cubeapis.com/docs)

### Requirements

Please consider using the following technologies:

- **Language:** Typescript or Javascript
- **Framework:** React.js (this could be in the form of any react framework, e.g. Next.js, Vite, Create React App)
- **Styling:** [Tailwind.css](https://tailwindcss.com/) (or similar utility based CSS frameworks)
- **Forms:** [React Hook Form](https://react-hook-form.com/) with yup validation ([see the docs on validation](https://react-hook-form.com/))
- **REST requests:** [Tanstack Query (useQuery)](https://tanstack.com/query/latest) - Combine this with [openapi-codegen](https://github.com/fabien0102/openapi-codegen) for auto generated hooks from our API documentation!

## API requests

Please read the [OpenAPI docs](https://cube-academy-api.cubeapis.com/docs) documentation before beginning.

You do not need to create a sign up and login flow (if you have time feel free to!) - this can be a one off request to obtain an authentication token to do further requests from.

The Authentication for the API must add a bearer token to authenticated requests.

E.g.

```
{
  "authorization": `Bearer ${token}`
}
```

## Submission

- The Submission must have version control history (.git directory) - this is essential so we can see how you went about implementing your solution.
- Can be zipped up and sent to us via [cubeacademy@3sidedcube.com](mailto:cubeacademy@3sidedcube.com?subject=Cube%20Academy%20Test) or hosted on GitHub.
- Please ensure that with your solution you include the following documentation (this can be included as part of a `README.md` or separate document)
  - A brief "Getting Started guide" on how to open the project locally
  - Did you have any challenges and if so, how did you overcome them?
  - Did you use any extra technologies and why?
  - Did you add any extra features?
  - If you had more time, what else would you implement?

## Questions?

If you have any questions about any of the above please get in touch with us at [cubeacademy@3sidedcube.com](mailto:cubeacademy@3sidedcube.com?subject=Cube%20Academy%20Test)
