#Resource Allocation in Distributed Cloud Gaming

Topic: Resource Allocation in Distributed Cloud Gaming
SDG Goal: SDG 9 – Industry, Innovation, and Infrastructure
Dataset: Steam Video Games

Project Overview

This project analyzes average playtime of top Steam games to determine resource allocation levels in a cloud gaming environment. By understanding which games are played the most, cloud gaming platforms can allocate computing resources efficiently to ensure smooth gameplay and reduce server overload.

Key Steps

Data Preprocessing:

Loaded the Steam dataset.

Filtered for 'play' actions only.

Converted playtime (hours) to float type.

Analysis:

Calculated average hours played per game.

Selected top 20 games by playtime.

Resource Allocation:

Defined thresholds for High, Medium, and Low Resource levels based on average hours.

Allocated resources accordingly.

Visualization:

Plotted a horizontal bar chart of top games vs. average play hours.

Resource allocation is indicated through analysis, helping cloud gaming providers optimize server usage.

Tools Used

Python (Pandas, Matplotlib)

Data Analysis & Visualization

Objective

Efficiently manage cloud resources for popular games, reducing latency, improving player experience, and supporting scalable cloud gaming infrastructure.
