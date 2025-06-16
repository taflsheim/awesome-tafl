# Awesome Tafl

A curated list of resources for Tafl games (also known as Hnefatafl or Viking Chess), covering rules, strategy, AI programming, and more.

## Contents

*   [Rules](#rules)
*   [Strategy](#strategy)
*   [AI Programming](#ai-programming)
    *   [General Concepts](#general-concepts)
    *   [Algorithms](#algorithms)
    *   [Evaluation Functions](#evaluation-functions)
*   [Code Repositories](#code-repositories)
*   [Tools](#tools)
*   [Communities](#communities)
*   [Related Games](#related-games)

## Rules

*   **Tafl Games - Wikipedia:** [https://en.wikipedia.org/wiki/Tafl_games](https://en.wikipedia.org/wiki/Tafl_games) - A general overview of Tafl games, their history, and common rule variations (Hnefatafl, Tablut, Tawlbwrdd, Brandubh, Ard Rí, Alea Evangelii).
*   **Hnefatafl: The Viking Game:** [https://aagenielsen.dk/](https://aagenielsen.dk/) - Comprehensive resource on Hnefatafl, including rules, history, and variants.
    *   **Hnefatafl Rules:** [https://aagenielsen.dk/hnefatafl_rules.php](https://aagenielsen.dk/hnefatafl_rules.php) - Specific rule sets for Hnefatafl.
*   **Cyningstan - Tafl Rules:** \[Link to specific rules page if available on Cyningstan] - Another source for Tafl rules and variants.
*   **Bead Game - How to Play Tafl**: [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEKghe2wRgTuzpYxIolcsNOEvsd41NrldlR3JZyqZ3A5YxDC1LFM_tnpPgvbQ3tDC5ezISqZoRbcLZiE82eA6I2X9Ukk6_kXPn51ZQWxj0HMxvElrniKDxtxhmM92V9MRqhJN3jb8g=](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQEKghe2wRgTuzpYxIolcsNOEvsd41NrldlR3JZyqZ3A5YxDC1LFM_tnpPgvbQ3tDC5ezISqZoRbcLZiE82eA6I2X9Ukk6_kXPn51ZQWxj0HMxvElrniKDxtxhmM92V9MRqhJN3jb8g=) - Simple instructions for Tafl.
*   **Bead Game - How to Play Irish Tafl (Brandub)**: [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHoVpgM-lO_31r9d7ODUXipe6INnQ8D4cBcO-fT5_VAm3zD9P-1iZsK5pEbjl5VvPwSkuyVFHDRa1IVNhkZYaa6kt0Fqr04LgN1K1vQjQJSns6THd3lMmS-_AY3wURtgIi0e4LUqhOZGmoVTAO1-ewnE1vgqQ=](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHoVpgM-lO_31r9d7ODUXipe6INnQ8D4cBcO-fT5_VAm3zD9P-1iZsK5pEbjl5VvPwSkuyVFHDRa1IVNhkZYaa6kt0Fqr04LgN1K1vQjQJSns6THd3lMmS-_AY3wURtgIi0e4LUqhOZGmoVTAO1-ewnE1vgqQ=) - Simple instructions for Brandub.

## Strategy

*   **Tafl Strategies - Cyningstan:** \[Link to specific strategy page if available on Cyningstan] - High-level strategic planning.
*   **Tim Millar's Tafl Pages:** \[Link to Tim Millar's page if available]- Strategic breakdowns by a top player.
*   **Hnefatafl: Tactics and Strategies - EG (YouTube):** [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGXFT0q5FFiEerD7VCrmd1X1ZjFVaV6v04Ty7qPOSilOB5RXh7hHWy0DAd_amJ35HEiXIJ3XigPeB7qDX9Rk4i6-XbF2LpbwMq07KTXrXAivEMQJ5IrRzv23QXRIrsFgKzyiYeYDg=](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGXFT0q5FFiEerD7VCrmd1X1ZjFVaV6v04Ty7qPOSilOB5RXh7hHWy0DAd_amJ35HEiXIJ3XigPeB7qDX9Rk4i6-XbF2LpbwMq07KTXrXAivEMQJ5IrRzv23QXRIrsFgKzyiYeYDg=) - Explains tactics and strategies for Hnefatafl.
*   **General Strategy for the Attackers | Hnefatafl: the Game of the Vikings:** [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE7dYcBH0LlemQ8sFCtPlwyiimzVNn0xdQyFLXNi1_hy8MaiHt8pFGqoQQgBe52z1Eflp6_fCmYwLy9rPboNTYV64zdVCrr4fcY0wau4CeIdVnb9fTmIDD83Bw5mFOgQRr4ghFmRsm68YdLhMLPAZ7TpclPh9VSyQvdlXu2g2A9](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQE7dYcBH0LlemQ8sFCtPlwyiimzVNn0xdQyFLXNi1_hy8MaiHt8pFGqoQQgBe52z1Eflp6_fCmYwLy9rPboNTYV64zdVCrr4fcY0wau4CeIdVnb9fTmIDD83Bw5mFOgQRr4ghFmRsm68YdLhMLPAZ7TpclPh9VSyQvdlXu2g2A9) - Focuses on attacker strategies like forming a blockade.
*   **Concise but good strategy advice:** [http://tafl.cyningstan.org.uk/page/29/forming-a-strategic-plan](http://tafl.cyningstan.org.uk/page/29/forming-a-strategic-plan)

## AI Programming

### General Concepts

*   **Minimax:** A classic game-playing algorithm that explores possible moves to a certain depth, assuming each player plays optimally.
    *   \[Add a brief explanation and links to resources explaining Minimax in general]
*   **Alpha-Beta Pruning:** An optimization technique for Minimax that reduces the search space.
    *   \[Add a brief explanation and links to resources explaining Alpha-Beta Pruning in general]
*   **Monte Carlo Tree Search (MCTS):** A modern approach to game AI that uses random playouts to estimate the value of different moves.  Combines reinforcement learning and tree search.
    *   \[Add a brief explanation and links to resources explaining MCTS in general]
*   **Neuroevolution:** Using evolutionary algorithms to train neural networks.
    *   \[Add a brief explanation and links to resources explaining Neuroevolution in general]

### Algorithms

*   **Minimax with Alpha-Beta Pruning:**
    *   `Bokhtiar-Adil/Vikings-chess-Hnefatafl`: [https://github.com/Bokhtiar-Adil/Vikings-chess-Hnefatafl](https://github.com/Bokhtiar-Adil/Vikings-chess-Hnefatafl) - A Python implementation of Minimax with alpha-beta pruning.
    *   `iitzco/TaflGamesMINIMAX`: [https://github.com/iitzco/TaflGamesMINIMAX](https://github.com/iitzco/TaflGamesMINIMAX) - Another Minimax implementation with alpha-beta pruning.
*   **Monte Carlo Tree Search (MCTS):**
    *   \[Add links to MCTS implementations or resources related to Tafl, when found]
*   **Neuroevolution:**
    *   Tafl-ES: \[Link to paper or repository if available] - Exploring Evolution Strategies for Tafl. *(See "Tafl-ES: Exploring Evolution Strategies for Asymmetrical Board Games" below)*

### Evaluation Functions

*   **King Safety:** Evaluating the safety and escape potential of the king (distance to escape, degree of surrounding).
*   **Material Advantage:** Counting the number of pieces remaining.
*   **Mobility:** Assessing the freedom of movement of pieces.
*   **Control of Key Squares:** Identifying and controlling important squares on the board (ranks, files, center).
*   **Blockade Completeness**
*   **Teaching a Computer to Play Hnefatafl:** [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHF_IH608ZlUmLMVBFD48_5PzfviP3mzczhnig8FlOYHbNVhcem7r_9p5wIDh2XEPPUwwD-CEWGlPZYtCrahP36CQr_RmWMkTuacchU9eVSkAQ2VMf39vQWKvpzpcjQAPuqmsd-B5eBu0GQzp-klB_QBGGxW8bJgbm66F5FjKVIFouzums=](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHF_IH608ZlUmLMVBFD48_5PzfviP3mzczhnig8FlOYHbNVhcem7r_9p5wIDh2XEPPUwwD-CEWGlPZYtCrahP36CQr_RmWMkTuacchU9eVSkAQ2VMf39vQWKvpzpcjQAPuqmsd-B5eBu0GQzp-klB_QBGGxW8bJgbm66F5FjKVIFouzums=) - Discusses several things to check for in an evaluation function.

## Code Repositories

*   `Bokhtiar-Adil/Vikings-chess-Hnefatafl`: [https://github.com/Bokhtiar-Adil/Vikings-chess-Hnefatafl](https://github.com/Bokhtiar-Adil/Vikings-chess-Hnefatafl) - Python, uses Minimax with alpha-beta pruning.
*   `demircancelebi/tafl`: [https://github.com/demircancelebi/tafl](https://github.com/demircancelebi/tafl) - TypeScript library for move generation/validation.  You need to implement the AI yourself.
*   `iitzco/TaflGamesMINIMAX`: [https://github.com/iitzco/TaflGamesMINIMAX](https://github.com/iitzco/TaflGamesMINIMAX) - Minimax with alpha-beta pruning.
*   `LFalch/hnefatafl`: [https://github.com/LFalch/hnefatafl](https://github.com/LFalch/hnefatafl) - Rust and PIXI.js.
*   `SolomonBaarda/Hnefatafl`: [https://github.com/SolomonBaarda/Hnefatafl](https://github.com/SolomonBaarda/Hnefatafl) - Unity Engine, C#.
*   `Ryan-Bauroth/Project02_PygAIme`: [https://github.com/Ryan-Bauroth/Project02_PygAIme](https://github.com/Ryan-Bauroth/Project02_PygAIme) - Deep Q-Learning approach.
*   `gallorob/tafl-gym`: [https://github.com/gallorob/tafl-gym](https://github.com/gallorob/tafl-gym) - OpenAI Gym environment for reinforcement learning in Tafl (Tablut variant by default).
*   `etandel/tafl`: [https://github.com/etandel/tafl](https://github.com/etandel/tafl) - An Open Tafl-compliant tafl engine.

## Tools

*   **OpenTafl:** [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF9f1t1ci2AEEq51EDDksIUP-7_skUW-uMKEY_-JDIof-f0joEquzEuVvVFSSJbff7PWEO9_BiC16yWY_XO_eAIp4T2yW8G9zAGfiHwbbl91m2A2x8dHMPVAf2zqYhSYYCw89LAGpAm2t5Xcbg0IyZhgEC2DZ-0Ke24TODCDzJ6azrsFHlZ93S-iVLt8RVHO0Eerw==](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQF9f1t1ci2AEEq51EDDksIUP-7_skUW-uMKEY_-JDIof-f0joEquzEuVvVFSSJbff7PWEO9_BiC16yWY_XO_eAIp4T2yW8G9zAGfiHwbbl91m2A2x8dHMPVAf2zqYhSYYCw89LAGpAm2t5Xcbg0IyZhgEC2DZ-0Ke24TODCDzJ6azrsFHlZ93S-iVLt8RVHO0Eerw==) - Open-source engine for board games in the hnefatafl family, supporting local human-on-human play, a built-in artificial intelligence, external AI engines.
*   \[Add links to any other tools that might be useful for Tafl development or analysis]

## Communities

*   **World Tafl Federation - Hnefatafl forum:** [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFakhvKKMfES1hnG6A4XRzoyLYqOCc4D2U5yAfA5dIDXLWT93d6qG8MlEhQEqsHaXEp3nHgYYZe5fkXRkZuFOhqBc4MZhPWSBFd4qyB7OP3BHjl3NZiCjYBBg8TXR5r6EdSt_-Q3sg-0CmIlIstx34d1MmQjd-GdnTd](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQFakhvKKMfES1hnG6A4XRzoyLYqOCc4D2U5yAfA5dIDXLWT93d6qG8MlEhQEqsHaXEp3nHgYYZe5fkXRkZuFOhqBc4MZhPWSBFd4qyB7OP3BHjl3NZiCjYBBg8TXR5r6EdSt_-Q3sg-0CmIlIstx34d1MmQjd-GdnTd)
*   **Tafl Gild (Facebook):** Scholarly debates on the historical aspects of tafl games. *(Note: Link may be needed)*
*   **Hnefatafl Mailing List:** A regular newsletter about the goings on in the Hnefatafl world (tournaments, etc.) - [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGvi2M6Zfy3JlGp7S-euiegPPQb4aHlTzZvR2rmGRQ6R1FbCvBMUTlzVvdI3kSiMWwC5c4-TH8MttoS1uAz-A4F1glvvNSwZupdocNil7q8VBjSd1Mb](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQGvi2M6Zfy3JlGp7S-euiegPPQb4aHlTzZvR2rmGRQ6R1FbCvBMUTlzVvdI3kSiMWwC5c4-TH8MttoS1uAz-A4F1glvvNSwZupdocNil7q8VBjSd1Mb)
*   \[Add links to other Tafl communities, forums, or social media groups]

## Related Games

*   **Chess:** A classic strategy board game that shares some similarities with Tafl.
    *   \[Add links to Chess programming resources, NNUE, etc.]
*   **Draughts (Checkers):** Another strategy board game with AI programming resources available.
*   Ludus Latrunculorum -- A Roman game that, at least as sometimes reconstructed, appears to be an ancestor of Tafl. ([4])
*   \[Add links to other board games with similar mechanics or strategic elements]

## Additional Resources

*   **Tafl-ES: Exploring Evolution Strategies for Asymmetrical Board Games:**  [https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHe822iAPlc_oFvSl0Ymqk_WeUGdxdhm8XUB3i3q1KsKf4aKCYD9zDhiVXe3MY3EeyQ4O_ZQnHELOA6XplmqjmKJxIulozIjKwcTEHOpKE6JSZ2yVeEhcOANFo1n_exNVDQgCDXyoweEa4KjKpehYt9af1QoSgtj27paXaq06du2BdAIzonREEqWyI-Z90YL1y4XWrf2dSVP-IWNpk=](https://vertexaisearch.cloud.google.com/grounding-api-redirect/AUZIYQHe822iAPlc_oFvSl0Ymqk_WeUGdxdhm8XUB3i3q1KsKf4aKCYD9zDhiVXe3MY3EeyQ4O_ZQnHELOA6XplmqjmKJxIulozIjKwcTEHOpKE6JSZ2yVeEhcOANFo1n_exNVDQgCDXyoweEa4KjKpehYt9af1QoSgtj27paXaq06du2BdAIzonREEqWyI-Z90YL1y4XWrf2dSVP-IWNpk=) - Paper exploring neuroevolution strategies (NES) for the asymmetrical nature of Tafl, co-evolving two populations of intelligent agents.
*   **gallorob/tafl-gym:** [https://github.com/gallorob/tafl-gym](https://github.com/gallorob/tafl-gym) - This Gym Environment was developed for and used in "Tafl-ES: Exploring Evolution Strategies for Asymmetrical Board Games".
