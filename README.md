# Data fetching code along workshop
We’ve explained that Next.js has two forms of pre-rendering: Static Generation and Server-side Rendering.Now, we’ll talk in depths about data fetching strategies for each case.

 We'll code the three unique Next.js functions you can use to fetch data for pre-rendering:

- getStaticProps (Static Generation): Fetch data at build time.
- [getStaticPaths](https://nextjs.org/learn/basics/data-fetching/with-data) (Static Generation): Specify dynamic routes to pre-render based on data.
- [getServerSideProps](https://nextjs.org/learn/basics/data-fetching/request-time) (Server-side Rendering): Fetch data on each request .


### Now code time
We’d like to create a note App, we'll view our notes, add new note, and view specific note.

1. Clone this repo
2. cd todo && npm i
3. check files
4. pgcli then \i path ofcreateDB.sql and build.sql
5. pgcli DB_URL from .env then \i path of build.sql
5. npm run dev
6. start from pages/index.js , You can notice that notes are static data try to fetch it by following comments.
7. When you finished go to pages/[id] , also follow the comments.

##### Have fun time :wink:
