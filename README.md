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
*   **Cyningstan - Tafl:** [http://tafl.cyningstan.com/](http://tafl.cyningstan.com/) - Another source for Tafl rules and variants.
*   **Bead Game - How to Play Tafl**: [https://www.bead.game/games/traditional/tafl](https://www.bead.game/games/traditional/tafl) - Simple instructions for Tafl.

## Strategy

*   **Tafl Strategies - Cyningstan:** [http://tafl.cyningstan.com/page/29/forming-a-strategic-plan](http://tafl.cyningstan.com/page/29/forming-a-strategic-plan) - High-level strategic planning.
*   **Tim Millar's Tafl Pages:** [https://web.archive.org/web/20130801173450/http://tim-millar.co.uk/section509308.html](https://web.archive.org/web/20130801173450/http://tim-millar.co.uk/section509308.html)- Strategic breakdowns by a top player (via [https://web.archive.org](archive.org)]
*   **Hnefatafl: Tactics and Strategies - EG (YouTube):** [https://www.youtube.com/watch?v=axzd_MM1rJ0](https://www.youtube.com/watch?v=axzd_MM1rJ0) - Explains tactics and strategies for Hnefatafl.

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
*   **Teaching a Computer to Play Hnefatafl:** [http://tafl.cyningstan.com/post/1053/teaching-a-computer-to-play-hnefatafl](http://tafl.cyningstan.com/post/1053/teaching-a-computer-to-play-hnefatafl) - Discusses several things to check for in an evaluation function.

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

*   **OpenTafl:** [https://github.com/jslater89/OpenTafl](https://github.com/jslater89/OpenTafl)- Open-source engine for board games in the hnefatafl family, supporting local human-on-human play, a built-in artificial intelligence, external AI engines.

## Communities

*   **World Tafl Federation - Hnefatafl forum:** [https://aagenielsen.dk/hnefataflforum/phpBB3/index.php?sid=713dbfb00d0e3d39a19569d870fd07c5](https://aagenielsen.dk/hnefataflforum/phpBB3/index.php?sid=713dbfb00d0e3d39a19569d870fd07c5)
*   **Tafl Gild (Facebook):** Scholarly debates on the historical aspects of tafl games. *(Note: Link may be needed)*

## Related Games

*   **Ludus Latrunculorum** [https://en.wikipedia.org/wiki/Ludus_latrunculorum](https://en.wikipedia.org/wiki/Ludus_latrunculorum) -- A Roman game that, at least as sometimes reconstructed, appears to be an ancestor of Tafl. 

## Additional Resources

*   **Tafl-ES: Exploring Evolution Strategies for Asymmetrical Board Games:** [https://link.springer.com/chapter/10.1007/978-3-031-08421-8_4](https://link.springer.com/chapter/10.1007/978-3-031-08421-8_4) - Paper exploring neuroevolution strategies (NES) for the asymmetrical nature of Tafl, co-evolving two populations of intelligent agents.
*   **gallorob/tafl-gym:** [https://github.com/gallorob/tafl-gym](https://github.com/gallorob/tafl-gym) - This Gym Environment was developed for and used in "Tafl-ES: Exploring Evolution Strategies for Asymmetrical Board Games".
