This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
## How to use it
In the “Pokemons” option, a series of Pokémon brought through the PokeAPI https://pokeapi.co/ is listed. This list is generated statically in the construction carried out in the deployment of the application.

![imagen](https://github.com/wilmer-energy/next-dashboard/assets/96258090/300a81a1-6547-42d8-bd2f-f1b2bf3a2d02)

By clicking on any of these pokemons, it will take us to a dynamic page that will give us more details about it. This app was programmed so that the corresponding page for each of the first 100 pokemons is generated statically in the construction process. of the application, those that remain after these first 100 are generated dynamically on the server when making the request for its corresponding page.

![imagen](https://github.com/wilmer-energy/next-dashboard/assets/96258090/f7676d77-335b-4e5c-b56c-9ebe91c11f2c)

In the “Favorites” option there is a list of pokemons which were previously added to the favorites by the user, this list is saved in the local memory of the browser “localStorage”.

![imagen](https://github.com/wilmer-energy/next-dashboard/assets/96258090/21a39adc-eb1c-4bda-bde0-cfce6a1788d1)

The “Counter” section shows the option to edit a counter, which with the help of Redux stores its value globally for the entire application, enabling the use of this value in other sections such as the dashboard.

![imagen](https://github.com/wilmer-energy/next-dashboard/assets/96258090/1971d31d-34af-440b-868c-5e68b90b379c)

## Getting Started

Install dependencies:

```bash
npm install
```
Run de app
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
