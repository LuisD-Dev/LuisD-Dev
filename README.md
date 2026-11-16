<img src="assets/profile-header.svg" width="100%" alt="Luis Diego Campos Murillo, Software Engineering Student and Junior Software Developer in Costa Rica. Illustrated route from Grecia to Poás." />

[LinkedIn](https://www.linkedin.com/in/luis-diego-campos-b1225b424)

I'm working toward a bachelor's degree in software engineering at Universidad Técnica Nacional. Most of my university projects start with a practical question. Can two students book the same lab? Which delivery should a driver make first? I use C#, React, and SQL Server for the applications, and C++ when I want to compare algorithms.

[Open-source contributions](#open-source-contributions) · [Selected projects](#selected-projects)

## Open-source contributions

| Project | What I worked on | Merged change |
| --- | --- | --- |
| **Velo** | I built an indexer for Stellar/Soroban escrow events. It records when funds are locked, released, or disputed in **PostgreSQL**. Clients can query the history through **GraphQL** or subscribe to live updates over **WebSocket**. | [PR #354](https://github.com/Nullifier-Systems/velo/pull/354) |
| **GuildPass** | I linked each **PostgreSQL** audit entry to the previous one using **SHA-256**. An administrator can verify the chain and locate the first entry affected by a change. | [PR #315](https://github.com/Adamantine-guild/guildpass-app/pull/315) |
| **Teclia Academy** | I used the official **Stripe** SDK in **Express** to verify payment notifications and made sure a retried event is processed only once. | [PR #89](https://github.com/Teclia-Academy/Teclia-Academy/pull/89) |
| **Nester** | I wrote **Rust** tests for privileged smart contract operations, including what happens after a user's role is revoked. The full suite passed all 396 tests in the PR. | [PR #797](https://github.com/Suncrest-Labs/nester/pull/797) |

## Selected projects

### Fleet Maintenance API

Oscar Rojas García and I built this API to track vehicles, work orders, and spare parts. A fleet manager can find parts running low and compare suppliers by price and delivery time. I used **ASP.NET Core** for the endpoints, **EF Core** to map the relationships in **SQL Server**, and **JWTs** to identify the signed-in user.

[Repository and API examples](https://github.com/LuisD-Dev/ProyectoFlota#readme) · [My sign-in implementation](https://github.com/LuisD-Dev/ProyectoFlota/commit/20b85650489e334c4a9906bcf6f8fe01d888724f)

### Lab Reservations

Our team built a booking system for UTN labs. The **React** form sends requests to a **C#** API that checks availability, opening hours, and who owns the booking. Reservations are stored in **SQL Server**.

I wrote tests for partial overlaps, such as a 10:30 booking in a lab already reserved until 11:00. I also set up **Azure Pipelines** to build the API and publish test results after each push to the main branch. The run documented in the pull request passed **209 tests**.

[Repository](https://github.com/LuisD-Dev/Reservas-Labs) · [Overlap tests](https://github.com/LuisD-Dev/Reservas-Labs/commit/2744e0402d209e888cdb29e6d202436dc1a5a204) · [CI pipeline](https://github.com/LuisD-Dev/Reservas-Labs/pull/14)

### CondoGest

A desktop app for condominium staff to look up a property's invoices and payments, reserve shared spaces, and check in visitors with QR codes. **WinForms** handles data entry, the **C#** business layer applies the rules, and **ADO.NET** reads and writes the records in **SQL Server**.

[Repository and manuals](https://github.com/LuisD-Dev/CondoGest_ISW524) · [Architecture notes](https://github.com/LuisD-Dev/CondoGest_ISW524/blob/main/ARQUITECTURA.md)

### Package Delivery Simulator

I modeled a delivery network in **C++** using an adjacency list and **Dijkstra's algorithm** to find the shortest route. Then I ran two dispatch strategies on the same network for the same number of simulation ticks. One serves urgent packages first. The other picks the nearest destination. I compare average wait time and completed deliveries to see how each choice affects the queue.

### Other work

- **Chema Style** — I worked on the **React** interface and used **Supabase** for application data.
- **Patitas CR** — A pet adoption website.
- **Teclia Academy** — A **React** learning platform with an **Express** API that manages access to course content by subscription tier. [Explore the project](https://github.com/LuisD-Dev/luis-rama/tree/develop)

<p><img src="https://skillicons.dev/icons?i=cs,dotnet,react,js,cpp,postgres,rust,git&theme=dark" alt="C#, .NET, React, JavaScript, C++, PostgreSQL, Rust, and Git" /></p>

[More merged contributions](https://github.com/pulls?q=is%3Apr+is%3Amerged+author%3ALuisD-Dev) · [All repositories](https://github.com/LuisD-Dev?tab=repositories)
