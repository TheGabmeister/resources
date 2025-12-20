# The Gabmeister Resources
This page is a collection of links I have found useful throughout my career (mostly Unity, Unreal, VR, and AR). I’m constantly updating this list, removing old items and adding new ones. I try to remove those that are older than 5 years old. However, there are exceptions which I truly believe contain information that are relevant today. 

One major shift that happened recently was the advent of AI. Large language models (LLMs) made a lot of beginner-level resources obsolete. We used to scavange the depths of online forums and stack overflow looking for "how-to" tutorials. Nowadays, we ask AI first, and do a search only if the answer is inadequate. This is why I will focus on resources that I think add value on top of what AI can already provide. 

The two biggest mistakes I did back when I was starting was getting into game engines and going straight into object-oriented programming (OOP) without understanding the fundamentals. I have never taken any formal computer science or game development education, so I just jumped straight into Unity and watched YouTube tutorials. Mainstream game engines do a lot of heavy lifting to abstract away the complexity happening under the hood. If you stay too long working on this abstraction layer, your knowledge and skills will plateau early, and it will be harder to tackle complex projects that require deeper understanding. That is why I recommend studying Assembly, C, C++, and non-OOP paradigms alongside learning game engines. If you have lots of time, I recommend making your own simple game engine just for learning. Get comfortable programming like how it was in the 90s, and gradually move up the abstraction layers.

Another best practice, if it's not already obvious, is to read the manual. The Unity and Unreal documentation, for example, are continously being updated. You would be surprised how much hidden gems are tucked away here. 

## Programming
```
"Talk is cheap. Show me the code."

- Linus Torvalds, creator of Linux -
```
### Learning Tips
- [The Hacker Mindset](https://dev.to/fluffynuts/the-hacker-mindset-p2f) (2019) by Davyd McColl
- [Just-In-Case vs. Just-In-Time Learning](https://hackernoon.com/just-in-case-vs-just-in-time-learning-c87f61d24360) (2018) by Osman (Ozzie) Ahmed Osman
- [How Developers Stop Learning: Rise of the Expert Beginner](https://daedtech.com/how-developers-stop-learning-rise-of-the-expert-beginner/) (2013) by Erik Dietrich

### Assembly
- Assembly Language for x86 Processors, 8th edition (2019) book by Kip R. Irvine
- [The Art of Picking Intel Registers](https://www.swansontec.com/sregisters.html) (2003) by William Swanson
- [Compiler Explorer](https://godbolt.org/)

### C
- [Tips for C Programming](https://www.youtube.com/watch?v=9UIIMBqq1D4) (2025) by Nic Barker
- [raylib vs SDL](https://gist.github.com/raysan5/17392498d40e2cb281f5d09c0a4bf798) (2022) by raysan5
- [Game State Pattern in C](https://gamedev.nokturnal.pl/posts/game-state-pattern-in-c/) (2011) by Paweł Góralski

### C++
- [LearnCpp.com](https://www.learncpp.com/)
- [An Introduction to Modern CMake](https://cliutils.gitlab.io/modern-cmake/) by Henry Schreiner
- [cmakeSetup](https://github.com/meemknight/cmakeSetup) by meemknight
- [C++ Core Guidelines](https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines.html) (2024) by Bjarne Stroustrup and Herb Sutter
- [C++ Game Programming](https://www.youtube.com/playlist?list=PL_xRyXins84_Sq7yZkxGP_MgYAH-Zo8Uu) (2024) by Dave Churchill
- [Thoughts on Modern C++ and Game Dev](https://www.elbeno.com/blog/?p=1598) (2019)
- [Data-Oriented Design and C++](https://www.youtube.com/watch?v=rX0ItVEVjHc) (2014) by Mike Acton

### Programming Principles and Patterns
- [Why Engineers Can't Be Rational About Programming Languages](https://spf13.com/p/the-hidden-conversation/) (2025) by Steve Francia
- [The Big OOPs: Anatomy of a Thirty-five-year Mistake](https://www.youtube.com/watch?v=wo84LFzx5nI) (2025) by Casey Muratori
- [Programming Principles](https://github.com/webpro/programming-principles) by Lars Kappert
- [Code The Rules, Script The Exceptions](https://www.youtube.com/watch?v=ljnaL7N5qtw) (2024) by Timothy Cain 
- [Simplicity](https://flaviocopes.com/simplicity/) (2024) by Flavio Copes
- [A Short Summary On Clean Coding Best Practices](https://codeburst.io/a-short-summary-on-clean-coding-best-practices-d8afbfa7677) (2021) by Thilina Ashen Gamage
- [Refactoring Guru](https://refactoring.guru/)
- [How Cohesion and Coupling Correlate](https://blog.ttulka.com/how-cohesion-and-coupling-correlate/) (2020) by Tomas Tulka
- [The Law of Demeter by Example](https://medium.com/vattenfall-tech/the-law-of-demeter-by-example-fd7adbf0c324) (2020) by Paweł Pluta
- [The Toolbox Fallacy](https://www.youtube.com/watch?v=sz4YqwH_6D0) (2019) by Passion of the Nerd
- [Object-Oriented Programming is Bad](https://www.youtube.com/watch?v=QM1iUe6IofM) (2016) by Brian Will
- [Getting rid of the OOP mindset](https://www.youtube.com/watch?v=GKYCA3UsmrU) (2015) by Casey Muratori
- [Game Programming Patterns](https://gameprogrammingpatterns.com/) (2014) by Robert Nystrom
- [Semantic Compression](https://caseymuratori.com/blog_0015) (2014) by Casey Muratori
- [“The Door Problem”](https://lizengland.com/blog/the-door-problem/) (2014) by Liz England
- [Tell Dont Ask](https://martinfowler.com/bliki/TellDontAsk.html) (2013) by Martin Fowler
- [Startup Suicide – Rewriting the Code](https://steveblank.com/2011/01/25/startup-suicide-%E2%80%93-rewriting-the-code/) (2011) by Steve Blank
- [Summary of “Clean Code” by Robert C. Martin](https://gist.github.com/cedrickchee/55ecfbaac643bf0c24da6874bf4feb08)
- [C³: Common Coding Conventions](https://github.com/tum-esi/common-coding-conventions)
- [Purely Functional Retrogames, Part 1](https://prog21.dadgum.com/23.html) (2008) by James Hague
- [The solution to ‘OOP is Bad’ : ECS](https://docs.spacestation14.com/en/robust-toolbox/ecs.html)
- [What is an Entity Component System architecture for game development?](https://www.richardlord.net/blog/ecs/what-is-an-entity-framework) () by Richard Lord
- [KISS and YAGNI](https://blog.codinghorror.com/kiss-and-yagni/) (2004) by Jeff Atwood
- [Orthogonality and the DRY Principle](https://www.artima.com/articles/orthogonality-and-the-dry-principle) (2003) A Conversation with Andy Hunt and Dave Thomas

## Game Engine Programming
- [Learn Game Engine Programming](https://engine-programming.github.io/)
- [Game Engine Architecture](https://www.gameenginebook.com/) by Jason Gregory
- [Rendering Engine Architecture Conference](https://enginearchitecture.org/)
- [Handmade Hero](https://www.youtube.com/playlist?list=PLnuhp3Xd9PYTt6svyQPyRO_AAuMWGxPzU)
- [Handmade Hero Notes](https://yakvi.github.io/handmade-hero-notes/)
- [Wookash Podcast](https://www.youtube.com/@WookashPodcast)
- [Rendering Engine Architecture Conference](https://enginearchitecture.org/)
- [Tools to make a Game Engine in C++](https://www.youtube.com/watch?v=qK-GTuhZwUg) (2022) by pikuma
- [Game Engine Black Book Doom](https://fabiensanglard.net/gebbdoom/)
- [Custom Game Engines: A Small Study](https://gist.github.com/raysan5/909dc6cf33ed40223eb0dfe625c0de74) (2020) by raysan5
- [How to write a game engine in pure C](https://prdeving.wordpress.com/2019/05/30/how-to-write-a-game-engine-in-pure-c-part-1-state-manager/) (2019) by PRDeving
- YouTube Series: [The Cherno Game Engine](https://www.youtube.com/playlist?list=PLlrATfBNZ98dC-V-N3m0Go4deliWHPFwT) (2018), [Kohi Game Engine](https://www.youtube.com/playlist?list=PLv8Ddw9K0JPg1BEO-RS-0MYs423cvLVtj) (2021)

## Unity
```
"I think the unmissable "skill" is the drive to create. 
If you have that drive, Unity will give you back thousandfold."

- David Helgason, Co-founder of Unity -
```

### Blogs and Articles
- [Technical deep dive: Unity best practices](https://unity.com/how-to)
- [Game Dev Digest](https://gamedevdigest.com/digests.html)

### Sample Projects
- [Parrot Game Sample](https://www.fab.com/listings/3b06d6ea-4185-472c-9783-22c329aae3fc) with [documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/parrot-game-sample-for-unreal-engine) (2025)
- [Unity Open Project #1: Chop Chop](https://github.com/UnityTechnologies/open-project-1) with [Wiki](https://github.com/UnityTechnologies/open-project-1/wiki) and [diagrams](https://miro.com/app/board/o9J_khLZ3kQ=/) (2021)
- [Multiplayer resource roundup](https://unity.com/blog/engine-platform/multiplayer-resource-roundup) (2024) by Daniel Crough
- [Start learning data-oriented design in Unity with these resources](https://unity.com/blog/engine-platform/dots-bootcamp-resources) (2024) by Fergus Baird

### Project Architecture and Programming Patterns
- [Unity Production Architecture](https://unity-architecture.com/) by Mody
- [Level up your code with design patterns and SOLID](https://unity.com/resources/design-patterns-solid-ebook) (2024) by Unity
- [Intro to Data Oriented Design for Games](https://www.youtube.com/watch?v=WwkuAqObplU) (2023) by Nic Barker
- [Create modular game architecture in Unity with ScriptableObjects](https://unity.com/resources/create-modular-game-architecture-with-scriptable-objects-ebook) (2023) by Unity
- [Functional Unity Architecture: A Developer’s Guide](https://medium.com/@bada/functional-unity-architecture-a-developers-guide-359e5111c5c2) 2023 by Bruno Mikoski
- [Simon Nordon's Game Architecture Case Studies](https://medium.com/@simon.nordon) (2023)
- [Level up your code with game programming patterns](https://unity.com/blog/games/level-up-your-code-with-game-programming-patterns) by Thomas Krogh-Jacobsen (2022). Complete PDF version [here](https://resources.unity.com/games/level-up-your-code-with-game-programming-patterns).
- [Game programming patterns in Unity](https://github.com/Habrador/Unity-Programming-Patterns) by Erik Nordeus
- [Unity Clean Code](https://github.com/sampaiodias/unity-clean-code) by Lucas Sampaio Dias
- [Unity Game Architecture](https://www.youtube.com/playlist?list=PLan3SCnsISTTnVHldjnrM5s18u6_BOuRz) (2022) by Hassan Habib
- [Three ways to architect your game with ScriptableObjects](https://unity.com/how-to/architect-game-code-scriptable-objects) (2020) by Unity
- [From Pong to 15 person project](https://www.youtube.com/watch?v=1le4vScG3gk) (2018) by Mikael Kalms
- [Game Architecture with Scriptable Objects](https://www.youtube.com/watch?v=raQ3iHhE_Kk) (2017) byRyan Hipple
- [Unity Architecture in Pokémon Go](https://www.youtube.com/watch?v=8hru629dkRY) (2016) by Chris Mortonson
- [Inversion of Control with Unity](https://www.sebaslab.com/ioc-container-unity-part-1/) (2012)

### C# Programming
- [Create a C# style guide: Write cleaner code that scales](https://unity.com/resources/create-code-c-sharp-style-guide-e-book) (2023) by Unity
- [DeltaTime](https://www.youtube.com/watch?v=yGhfUcPjXuE) (2023) by Jonas Tyroller
- [How to get a variable from another script in Unity](https://gamedevbeginner.com/how-to-get-a-variable-from-another-script-in-unity-the-right-way/) (2020) by John French
- [How to Get Variables from Other Scripts in Unity](https://www.youtube.com/watch?v=7gRrujBjsFo) (2020) by Jason Storey
- [Best practices: Async vs. coroutines](https://www.youtube.com/watch?v=7eKi6NKri6I) (2019) by Johannes Ahvenniemi
- [GUID Based reference workflow for System Shock 3](https://www.youtube.com/watch?v=6lRzXqfMXRo) (2019) by William Armstrong

### Profiling, Debugging, Optimization
- [Ultimate guide to profiling Unity games](https://unity.com/resources/ultimate-guide-to-profiling-unity-games) (2023)
- [Optimize your game performance for mobile](https://unity.com/resources/unity-e-book-optimize-your-mobile-game-performance) (2023)
- [Optimize your console and PC game performance](https://unity.com/resources/optimize-your-console-and-pc-game-performance) (2023)
- [BatchRendererGroup sample: Achieve high frame rate even on budget devices](https://unity.com/blog/engine-platform/batchrenderergroup-sample-high-frame-rate-on-budget-devices) (2023) by Arnaud Carre
- [Advanced Editor scripting hacks to save you time, part 2](https://unity.com/blog/engine-platform/advanced-editor-scripting-hacks-to-save-you-time-part-2) (2022) by Jordi Caballol
- [Advanced Editor scripting hacks to save you time, part 1](https://unity.com/blog/engine-platform/advanced-editor-scripting-hacks-to-save-you-time-part-1) (2022) by Jordi Caballol
- [Watch This Before Working on a Big Game in Unity](https://www.youtube.com/watch?v=kML67qB9Chk) (2022) by John Leorid
- [Performance optimization tips: Physics in Unity](https://www.youtube.com/watch?v=pTz3LMQpvfA) (2021) by Unity 
- [Optimization tips for maximum performance – Part 1](https://www.youtube.com/watch?v=ZRDHEqy2uPI) (2020) by Unity 
- [Optimization tips for maximum performance – Part 2](https://www.youtube.com/watch?v=EK8sX8oCQbw) (2020) by Unity 
- [Fixing Performance Problems](https://learn.unity.com/tutorial/fixing-performance-problems-2019-3-1) (2020) by Unity 
- [Unity's Evolving Best Practices](https://www.youtube.com/watch?v=W45-fsnPhJY) (2018) by Unity
- [Squeezing Unity: Tips for raising performance](https://www.youtube.com/watch?v=_wxitgdx-UI) (2017) by Unity 
- [Unity Draw Call Batching: The Ultimate Guide](https://thegamedev.guru/unity-performance/draw-call-optimization/) (2020) by Ruben Torres Bonet
- [Event Performance: C# vs. UnityEvent](https://www.jacksondunstan.com/articles/3335) (2016) by Jackson Dunstan
- [Unity Optimization Tips: Mobile & Desktop](https://makaka.org/unity-tutorials/optimization) (2022) by Makaka Games

### Graphics
- [When Optimisations Work, But for the Wrong Reasons](https://www.youtube.com/watch?v=hf27qsQPRLQ) (2024) by SimonDev
- [Accessing texture data efficiently](https://unity.com/blog/engine-platform/accessing-texture-data-efficiently) (2023) by Nico Leyman
- [Unity for technical artists: Key toolsets and workflows](https://unity.com/resources/unity-for-technical-artists-key-toolsets-and-workflows) (2022)
- [Lightmapping Troubleshooting Guide](https://discussions.unity.com/t/lightmapping-troubleshooting-guide/895352) (2022) by Kristijonas Jalnionis
- [Deep dive with post processing color grading](https://www.youtube.com/watch?v=1w9p-CrZYCU) (2020) by Nicolas Borromeo and Daniel Sanchez
- [Optimizing Graphics in Unity](https://learn.unity.com/tutorial/optimizing-graphics-in-unity) (2018) by Unity 

### Addressables
- [Addressables: Planning and best practices](https://unity.com/blog/engine-platform/addressables-planning-and-best-practices) (2023) by Jeff Riesenmy
- [Extended Q&A: Optimizing memory and build size with Addressables](https://unity.com/blog/engine-platform/extended-q-a-optimizing-memory-and-build-size-with-addressables) (2023) by Patrick Devarney

### UI
- [Unity UI Toolkit vs UGUI](https://www.angry-shark-studio.com/blog/unity-ui-toolkit-vs-ugui-2025-guide/)

### Networking / Multiplayer
- [The ultimate guide to multiplayer networking for advanced Unity developers](https://unity.com/resources/ultimate-guide-advanced-multiplayer-networking) (2024)
- [Going multiplayer: How to help your studio and game thrive](https://www.youtube.com/watch?v=UiAhrW8i7oA) (2024) by Paolo Abela
- [Unity Realtime Multiplayer](https://hackernoon.com/unity-realtime-multiplayer-part-1-networking-basics) (2023) by Dimitrii Ivashchenko
- [Multiplayer Game Architecture in Unity](https://www.youtube.com/watch?v=77vYKsXC4IE) (2020) by Shrine Wars
- [High Performance Game Networking in Unity3D + Q&A](https://www.youtube.com/watch?v=5b6k_ywdjw4) (2019) by Kyle Olsen and Jason Weimann
- [Netcode for GameObjects Bitesize Samples](https://github.com/Unity-Technologies/com.unity.multiplayer.samples.bitesize)

### Free Assets and Plugins
- [Unity guid-based-reference](https://github.com/Unity-Technologies/guid-based-reference)
- [Unity HFSM](https://github.com/Inspiaaa/UnityHFSM)
- [PrimeTween](https://github.com/KyryloKuzyk/PrimeTween) and [LitMotion](https://github.com/annulusgames/LitMotion)
- [Unity toolbar extender](https://github.com/marijnz/unity-toolbar-extender)
- [Fast Script Reload](https://github.com/handzlikchris/FastScriptReload)
- [Asset Usage Detector](https://github.com/yasirkula/UnityAssetUsageDetector)

## Unreal Engine
```
“Within our lifetimes, we will be able to push out 
enough computational power to simulate reality.”

- Tim Sweeney, CEO of Epic Games -
```

### Sample Projects
- [Lyra Sample Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/lyra-sample-game-in-unreal-engine) with [learning path](https://dev.epicgames.com/community/learning/paths/Z4/lyra-starter-game)
- [Parrot Game Sample](https://dev.epicgames.com/documentation/en-us/unreal-engine/parrot-game-sample-for-unreal-engine) with [video](https://www.youtube.com/watch?v=G8GrRA-8BHA) and [documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine/parrot-game-sample-for-unreal-engine)
- [ActionRPG](https://github.com/vahabahmadvand/ActionRPG_UE5) updated to UE5
- [Action Roguelike C++](https://github.com/tomlooman/ActionRoguelike) by Tom Looman

### Project Management, CI/CD, Version Control
- [Setting up an Unreal Engine Studio the Epic Way](https://dev.epicgames.com/community/learning/tutorials/8JYW/epic-for-indies-setting-up-an-unreal-engine-studio-the-epic-way) (2024) by Ari Arnbjörnsson
- [Workflow Best Practices & Avoiding Common Pitfalls with Perforce & UE](https://www.youtube.com/watch?v=A8JzPKlHz8o) (2024) by Ryan Maffesoli

### Conventions
- [Coding Standard](https://dev.epicgames.com/documentation/en-us/unreal-engine/epic-cplusplus-coding-standard-for-unreal-engine) in docs
- [Unreal Engine 5 Style Guide](https://github.com/Allar/ue5-style-guide) by Michael Allar
- [Open Unreal Conventions](https://jonasreich.github.io/OpenUnrealConventions/) by Jonas Reich

### C++ / Blueprints
- [UPROPERTY](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-uproperties) in docs
- [Actor Lifecycle](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-actor-lifecycle) in docs
- [Advanced Blueprinting Techniques](https://www.youtube.com/watch?v=IIr4-cpbKog) (2024) by Matt Oztalay
- [De-spaghetti Your Blueprints, the Scientific Way](https://www.youtube.com/watch?v=1SH9DBlfE4I) (2024) by Valentin Galea
- [Navigating Enhanced Input in UE & Conquering Common Challenges](https://www.youtube.com/watch?v=iV5HygiBwGE) (2024) by Thomas Sheppard and Hayden Simpson
- [Lessons Learned From A Year of Unreal Engine AAA Development](https://www.youtube.com/watch?v=U0RCO0id1kI) (2022) by Ari Arnbjörnsson
- [Building Tools Quickly: Blueprints, Menus, Utilities, and Widgets](https://www.youtube.com/watch?v=wJqOn88cU7o) (2022) by Paul Greveson
- [Exploring the Gameplay Ability System (GAS) with an Action RPG](https://www.youtube.com/watch?v=tc542u36JR0) (2022) by Sam Pike
- [Blueprints vs. C++: How They Fit Together and Why You Should Use Both](https://www.youtube.com/watch?v=VMZftEVDuCE) (2021) by Alex Forsythe
- [Unreal Engine C++ Project Setup, From Scratch](https://www.youtube.com/watch?v=94FvzO1HVzY) (2020) by Alex Forsythe
- [Unreal Engine C++ Complete Guide](https://www.tomlooman.com/unreal-engine-cpp-guide/) (2023) by Tom Looman
- [Unreal C++ speedrun](https://landelare.github.io/2023/01/07/cpp-speedrun.html) (2023) by Laura Andelare
- Mr Robin’s [Guide to Unreal Engine C++](https://github.com/MrRobinOfficial/Guide-UnrealEngine)
- [Balancing Blueprint and C++](https://dev.epicgames.com/documentation/en-us/unreal-engine/balancing-blueprint-and-cplusplus?application_version=4.27) and [learning course](https://dev.epicgames.com/community/learning/courses/bY/unreal-engine-balancing-blueprint-and-c-in-game-development/LdK/introduction-to-the-course) and [another learning course](https://dev.epicgames.com/community/learning/courses/NGA/unreal-engine-balancing-blueprints-and-c/e9xq/unreal-engine-balancing-blueprints-and-c-overview)
- [What is Class Default Object?](https://forums.unrealengine.com/t/what-is-cdo/310820)

### Project Architecture and Design Patterns
- [Components vs Interfaces vs Abstract Classes (When to Use What?)](https://www.youtube.com/watch?v=tYwN7XPayhE) (2024) by AmrMakesGames
- [The Unreal Engine Game Framework: From int main() to BeginPlay](https://www.youtube.com/watch?v=IaU2Hue-ApI) (2020) by Alex Forsythe
- [State Design Pattern in Unreal Engine Blueprint](https://www.youtube.com/watch?v=Eh-ONuMYADA) (2020) by Paul Gestwicki


### Data Management
- [Working with Data in Unreal Engine](https://dev.epicgames.com/community/learning/tutorials/Gp9j/working-with-data-in-unreal-engine-data-tables-data-assets-uproperty-specifiers-and-more) (2024) with [video](https://www.youtube.com/watch?v=HOpyZ8552oA) by JackDCondon
- [Unreal Engine Data Roundtable Discussion](https://www.youtube.com/watch?v=6-N-j6W-DhE) (2022) by benui
- [Data-driven Design in Unreal](https://unreal-garden.com/tutorials/data-driven-design/) (2020) by benui

### Physics and Collision
- [Tips and Tricks for Chaos Destruction](https://www.youtube.com/watch?v=zFiHDRREv7E) (2025) by Xiao Yue
- [Practical Tips for Managing Collision Settings & Queries](https://www.youtube.com/watch?v=xIQI6nXFygA) (2023) by George Prosser
- [The Gritty Reality of Real-Time Cloth and Rigid-Body Character Physics](https://www.youtube.com/watch?v=4NkNBImONJU) (2022) by Tim Brakensiek

### AI
- [Designing and Implementing Your Game’s AI Architecture in UE](https://www.youtube.com/watch?v=a3bHkVDZuYU) (2024) by Maciej Sulinski

### UI and Localization
- [Tech Art Chronicles: UMG Tips and Tricks](https://joyrok.com/UMG-Layouts-Tips-and-Tricks)
- [Best Practices for Creating and Managing Widgets](https://www.youtube.com/watch?v=7b7a20j0azc) (2023) by Kekdot
- [How to create Modular and Scalable UI systems](https://www.youtube.com/watch?v=v9k-J2GeEKI) (2023) by AmrMakesGames
- [Advanced UI Templating Techniques using Widget Blueprints and Materials](https://www.youtube.com/watch?v=dSTdAToJ7Gg) (2022) by Adrienne Pugh
- [Optimizing and Building UI for AAA Games](https://www.youtube.com/watch?v=OyY3OYbNK7s) (2020) by Carey Hickling
- [Unreal UI Best Practices](https://unreal-garden.com/tutorials/ui-best-practices/) (2019) by benui
- [Unreal UIs and Localization](https://unreal-garden.com/tutorials/ui-localization/) (2017) by benui 
- [Unreal Garden](https://unreal-garden.com/) UI Tutorials

### Profiling, Debugging, and Optimization
- [Beyond Print String](https://dev.epicgames.com/community/learning/talks-and-demos/WDmB/beyond-print-string-debugging-unreal-engine-lightning-round-unreal-fest-bali-2025) (2025) by Matt Oztalay
- [The Great Hitch Hunt: Tracking Down Every Frame Drop](https://dev.epicgames.com/community/learning/tutorials/6XW8/unreal-engine-the-great-hitch-hunt-tracking-down-every-frame-drop) (2025) by Ari Arnbjörnsson
- [Game Engines & Shader Stuttering: UE's Solution](https://dev.epicgames.com/community/learning/tutorials/xjzE/unreal-engine-epic-for-indies-game-engines-shader-stuttering-ue-s-solution) (2025) by Ari Arnbjörnsson
- [Performance Tips & Tricks - Animation](https://dev.epicgames.com/community/learning/knowledge-base/xBZp/unreal-engine-performance-tips-tricks-animation) (2025) by Euan Carmichael
- [Myth-busting "Best Practices" in Unreal Engine](https://dev.epicgames.com/community/learning/tutorials/l3E0/myth-busting-best-practices-in-unreal-engine) (2024) by Ari Arnbjörnsson
- [Optimizing the Game Thread](https://www.youtube.com/watch?v=KxREK-DYu70) (2024) by Jake Simpson
- [Advanced Debugging in Unreal Engine](https://dev.epicgames.com/community/learning/tutorials/dXl5/advanced-debugging-in-unreal-engine) (2023) by Ari Arnbjörnsson
- [Asset Dependency Chains: The Hidden Danger](https://www.youtube.com/watch?v=4-oRyDLfo7M) (2022) by Mark Craig
- [Unreal Engine Game Optimization on a Budget](https://www.tomlooman.com/unrealengine-optimization-talk/) (2022) by Tom Looman
- [Deep Dive: Memory Management in Blueprints](https://www.jesseleehumphry.com/post/deep-dive-memory-management-in-blueprints) (2020) by Jesse Humphy
- [Deep Dive: Memory Management in Blueprints II](https://www.jesseleehumphry.com/post/deep-dive-memory-management-in-blueprints-ii) (2020) by Jesse Humphy
- [Profiling and Optimization in UE4](https://www.youtube.com/watch?v=EbXakIuZPFo) (2019) by Paulo Souza

### Graphics Optimization
- [Optimizing and Debugging Projects for Real-Time Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/optimizing-and-debugging-projects-for-real-time-rendering-in-unreal-engine) in documentation
- [1-hour of Unreal GPU Optimization Tips & Tricks](https://www.youtube.com/watch?v=c2MH20OPSw0) (2025) by Tom Looman
- [Optimizing UE5: Advanced Rendering, Graphics Performance, and Memory Management](https://www.youtube.com/watch?v=dj4kNnj4FAQ) (2024) by Matt Oztalay
- [Optimizing UE5: Rethinking Performance Paradigms for High-Quality Visuals - Part 1](https://dev.epicgames.com/community/learning/talks-and-demos/Vpv2/unreal-engine-optimizing-ue5-rethinking-performance-paradigms-for-high-quality-visuals-part-1-nanite-and-lumen-unreal-fest-2023) (2023) by Matt Oztalay
- [Optimizing UE5: Rethinking Performance Paradigms for High-Quality Visuals - Part 2](https://dev.epicgames.com/community/learning/talks-and-demos/VlO2/unreal-engine-optimizing-ue5-rethinking-performance-paradigms-for-high-quality-visuals-pt-2-supporting-systems-unreal-fest-2023) (2023) by Matt Oztalay
- [Vegetation Best Practices for UE5](https://dev.epicgames.com/community/learning/talks-and-demos/2lyj/unreal-engine-vegetation-best-practices-for-ue5) (2023) by Nils Arenz
- [Shader Optimization – True Instruction Cost, Performance Tips](https://www.youtube.com/watch?v=y0QASid1v8w) (2022) by Tech Art Aid
- [Unreal Art Optimization](https://unrealartoptimization.github.io/) by Oskar Świerad
- [Performance Optimization for Environments](https://www.youtube.com/watch?v=ZRaeiVAM4LI) (2020) by Matt Oztalay and Jakob Keudel

### Lighting, Rendering, and Shaders
- [Advanced Rendering and Debugging Tips](https://www.youtube.com/watch?v=ICA0ZGMfufI) (2024) by Nori Shinoyama and Yutaro Sawada
- [The Journey to Nanite](https://www.youtube.com/watch?v=NRnj_lnpORU) (2022) by Brian Karis
- [A Deep Dive into Nanite Virtualized Geometry](https://www.youtube.com/watch?v=eviSykqSUUw) (2021) by Brian Karis, Rune Stubbe, Graham Wihlidal
- [An In-Depth Look at Real-Time Rendering](https://www.unrealengine.com/en-US/onlinelearning-courses/an-in-depth-look-at-real-time-rendering) (2019) by Sjoerd de Jong

### Animation
- [Unreal Engine 5 Character and Animation Optimizations](https://www.youtube.com/watch?v=N_suMyUuork) (2024) by Matthew Lake

### Mobile
- [Unreal for Mobile: Building AAA Cross-Platform Open Worlds](https://www.youtube.com/watch?v=nZlVkI3j7Xs) (2024) by Arvind Neelakantan
- [Building AAA Mobile Games with Unreal Engine](https://www.youtube.com/watch?v=QbskVTJrWRI) (2024) by Arvind Neelakantan
- [Mobile UI Performance Tips](https://www.youtube.com/watch?v=R-SRTLs4wjI) (2024) by Cody Albert
- [Advanced Development and Debugging for Android/iOS](https://www.youtube.com/watch?v=jQX2SFuKN9s) (2022) by Dmytro Vovk and Axel Riffard

### Networking / Multiplayer
- [Unreal Engine Multiplayer Tips and Tricks](https://wizardcell.com/unreal/multiplayer-tips-and-tricks/) by WizardCell
- [Persistent Data Compendium](https://wizardcell.com/unreal/persistent-data/) by WizardCell
- [Multiplayer Network Compendium](https://cedric-neukirchen.net/docs/category/multiplayer-network-compendium/) by Cedric Neukirchen
- [The Secret of Multiplayer | Ownership](https://www.youtube.com/watch?v=k4_n5LD5Ees) (2021) by Aaron Hunt
- [Multiplayer in Unreal Engine: How to Understand Network Replication](https://www.youtube.com/watch?v=JOJP0CvpB8w) (2020) by Alex Forsythe
- [Unreal Engine Multiplayer Framework](https://www.youtube.com/watch?v=Hsr6mbNKBLU) (2022) by Kekdot
- <https://unreal-mmo-dev.com>
- [Kieran Newland Blog](https://www.kierannewland.co.uk/blog/)
- [Devtricks blog](https://vorixo.github.io/devtricks/) by Alvaro Jover-Alvarez

### Epic Online Servies
- [Creating Scalable Multiplayer Experiences](https://www.youtube.com/watch?v=h2Tr8Lk8hXI) (2024) by Ryan Maloney
- [Epic Online Services: Developer Tips and Tricks](https://www.youtube.com/watch?v=-RrA41fYQlc) (2024) by James White

### Pixel Streaming
- [Pixel Streaming documentation](https://docs.unrealengine.com/5.2/en-US/pixel-streaming-in-unreal-engine/)
- [Interacting with the Pixel Streaming System](https://docs.unrealengine.com/5.2/en-US/interacting-with-the-pixel-streaming-system-in-unreal-engine/)
- [Pixel Streaming servers and frontend GitHub repo](https://github.com/EpicGames/PixelStreamingInfrastructure)
- [Frontend Communication with Unreal Engine Client](https://www.youtube.com/watch?v=lBR3yQuztqI) (2023) by Betide Studio
- [Voice Chat with Unreal Engine Client](https://www.youtube.com/watch?v=bg0nGVlzfgg) (2023) by Betide Studio
- [How to Pixel Stream Unreal Engine 5.2 on AWS Instance (Windows)](https://www.youtube.com/watch?v=vviTeRnVlHk) (2023) by Eagle 3D Streaming
- [4Players ODIN - Voice Chat SDK](https://www.unrealengine.com/marketplace/en-US/product/4players-odin-sdk) compatible with pixel streaming

### Crash Troubleshooting
- [GPU Crash Debugging in Unreal Engine: Tools, Techniques, and Best Practices](https://www.youtube.com/watch?v=CyrGLMmVUAI) (2023) by Thijs van Wingerden
- [Crashing With Style in Unreal Engine](https://www.youtube.com/watch?v=ow__LgMF5gE) (2022) by Ari Arnbjörnsson
- [What do you do when Unreal Editor crashes?](https://www.youtube.com/watch?v=TXZGIvpEhW8) (2020) by Alex Forsythe
- [Crash Reporting](https://dev.epicgames.com/documentation/en-us/unreal-engine/crash-reporting-in-unreal-engine) in Unreal Engine. **NOTE**: Download ***Editor symbols for debugging*** if you're using Unreal Engine from the Epic Launcher. These will allow the Crash Reporter to show you a detailed call stack. Moreover, the Crash Reporter does not show up when you're using a UE5 Editor Source Build from GitHub. Instead, you need to run Debug Mode in Visual Studio.

### 2D
- [Optimal Post Process Settings / 2D Pixel Art](https://ue5study.com/2d/ue5-2d-postprocess-settings/)

### Others
- [I Wish I Learned This Sooner!](https://www.youtube.com/watch?v=m0T8euG9Rh8) (2024) by Alex Coulombe
- [The Unfeatured Features of Unreal Engine](https://www.youtube.com/watch?v=_BIZ3FOcLNs) (2024) by Chris Murphy
- [How to integrate third-party library into Unreal Engine](https://georgy.dev/posts/third-party-integration/)\

### Blogs, Articles, and YouTube channels
- [Unreal Engine Tech Blogs](https://www.unrealengine.com/en-US/feed?tags=tech-blog)
- [Unreal Engine Learning Library](https://dev.epicgames.com/community/unreal-engine/learning)
- [Ari's Unreal Engine Notes](https://flassari.notion.site/Ari-s-Unreal-Engine-Notes-1a75e43f4014464984d4fae0617e5cef)
- [ari.games](https://ari.games/)
- [Unreal Engine Community Wiki](https://unrealcommunity.wiki/)
- [Tom Looman](https://www.tomlooman.com/)
- [Unreal Engine Learning Resources](https://www.tomlooman.com/unreal-engine-resources/) by Tom Looman
- [Laura's (Mostly) Unreal Blog](https://landelare.github.io/)
- [Unreal Directive](https://unrealdirective.com/) by Dylan "Tezenari" Amos
- [Tech Art Aid](https://www.youtube.com/@TechArtAid/videos) by Oskar Świerad

## Godot
- [How to Minify Godot's Build Size (93MB -> 6.4MB exe)](https://popcar.bearblog.dev/how-to-minify-godots-build-size/)
- [This is THE way to implement interfaces in Godot](https://xynanlee.substack.com/p/this-is-the-way-to-implement-interfaces) (2025) by Xynan Lee
- [Enjoyable Game Architecture](https://chickensoft.games/blog/game-architecture) (2023) by Joanna May 

## XR
```
"Unfortunately, no one can be told what the Matrix is.
You have to see it for yourself."

- Morpheus, The Matrix (1999) -
```
### Meta Quest
- [Meta Horizon OS Developers](https://developers.meta.com/horizon/develop/)
- [Code Samples](https://developer.oculus.com/code-samples/)
- [Capture MR and VR Apps for Publishing](https://developers.meta.com/horizon/resources/video-capture-mr-vr/)
- [Building Content to Optimize User Time](https://developers.meta.com/horizon/blog/optimize-user-time-goldilocks-session-length-meta-quest/) (2025)
- [Making a Mesh: Global Mesh Destruction in First Encounters](https://developers.meta.com/horizon/blog/scene-mesh-destruction-first-encounters-meta-quest-developers-mixed-reality/) (2023)
- [How to Improve Unreal Engine Material Shader with Adreno Offline Compiler](https://developers.meta.com/horizon/blog/unreal-engine-adreno-offline-compiler-meta-quest/) (2023)
- [Improve App Image Quality with Meta Quest Super Resolution](https://developers.meta.com/horizon/blog/vr-image-quality-meta-quest-super-resolution/) (2023)
- [Project Flowerbed: A WebXR Case Study](https://developers.meta.com/horizon/blog/project-flowerbed-a-webxr-case-study/) (2023)
- [The Evolution & Implementation of Hand Tracking in ‘Myst’](https://developers.meta.com/horizon/blog/the-evolution-and-implementation-of-hand-tracking-in-myst/) (2022)
- [Building Your Multiplayer VR Experience](https://developers.meta.com/horizon/blog/building-your-multiplayer-vr-experience-platform-sdk-and-unity-sharedspaces-sample/) (2022)
- [Showdown on Quest Part 1](https://developers.meta.com/horizon/blog/showdown-on-quest-part-1-how-app-spacewarp-improves-performance-/) (2022) by Zac Drake
- [Getting a Handle on Meta Quest Memory Usage](https://developers.meta.com/horizon/blog/getting-a-handle-on-meta-quest-memory-usage/) (2022)
- [Oculus Multiplayer Development Quick Start Guide](https://developers.meta.com/horizon/blog/oculus-multiplayer-development-quick-start-guide/) (2022)
- [Avoiding Hitches When Loading Scenes in Unity](https://developers.meta.com/horizon/blog/avoiding-hitches-when-loading-scenes-in-unity/) (2021)
- [Unity Profiler & Profile Analyzer Data on Quest](https://developers.meta.com/horizon/blog/get-started-with-the-unity-profiler-amp-profile-analyzer-data-on-quest/) (2021)
- [Using Vulkan Subpasses in UE4 for Performant Tone Mapping on Quest](https://developers.meta.com/horizon/blog/graphics-showcase-using-vulkan-subpasses-in-ue4-for-performant-tone-mapping-on-quest/) (2021)
- [Unreal Insights on Oculus Quest](https://developers.meta.com/horizon/blog/get-started-with-unreal-insights-on-the-oculus-quest/) (2021)
- [Optimizing Performance For Fast-Paced Interactions on Quest](https://developers.meta.com/horizon/blog/developer-perspective-optimizing-performance-for-fast-paced-interactions-on-quest/) (2019)

### Meta Developers YouTube Channel
- [State of Compute: Maximizing Performance on Meta Quest](https://www.youtube.com/watch?v=M6RKMXQbtWk) (2023)
- [Developing Marvel’s Iron Man VR for Meta Quest](https://www.youtube.com/watch?v=Z0be5hidNBk) (2023)
- [Performance and Optimization on Meta Quest Platform](https://www.youtube.com/watch?v=5Tll_sYZ83w) (2022)
- [State of the Art GPU Profiling on Quest l Facebook Connect](https://www.youtube.com/watch?v=0qMyqYiqnvk) (2021) by Meta Quest

### XR in Unreal Engine
- [XR Best Practices](https://dev.epicgames.com/documentation/en-us/unreal-engine/xr-best-practices-in-unreal-engine) in UE Documentation
- [XR Performance and Profiling](https://dev.epicgames.com/documentation/en-us/unreal-engine/xr-performance-and-profiling-in-unreal-engine) in UE Documentation
- [Using UE5 to Build Modern VR Action Games]() (2024) by Alex Silkin
- [Profiling with Stereo Rendering](https://dev.epicgames.com/community/learning/tutorials/bOLv/unreal-engine-profiling-with-stereo-rendering-xr) (2024) by Epic Online Learning
- [What You Didn’t Know About VR Development in Unreal Engine](https://www.youtube.com/watch?v=vT1T2unF8EI) (2023)
- [What are the Performance-killer for VR?](https://forums.unrealengine.com/t/what-are-the-performance-killer-for-vr-eg-oculusquest2-all-postprocess-all-screen-space/248143) (2021) in UE Forums
- [Oculus Quest Performance Tools in Unreal Engine](https://medium.com/realities-io/oculus-quest-performance-tools-in-unreal-engine-2210f2581c8f) (2020) by Shahriar Shahrabi

### XR in Unity
- [XR](https://docs.unity3d.com/6000.1/Documentation/Manual/XR.html) in Docs
- [VR Template](https://docs.unity3d.com/Packages/com.unity.template.vr@9.1/manual/index.html) in Docs
- [Mixed Reality Template](https://docs.unity3d.com/Packages/com.unity.template.mixed-reality@2.1/manual/index.html) in Docs
- [XR Interaction Toolkit](https://docs.unity3d.com/Packages/com.unity.xr.interaction.toolkit@3.2/manual/index.html) in Docs
- [Performance recommendations for Unity](https://learn.microsoft.com/en-us/windows/mixed-reality/develop/unity/performance-recommendations-for-unity) (2022) in Microsoft Documentation
- [VR Optimization and Performance Tips for Unity](https://www.youtube.com/watch?v=xqgt9W4Zrjg) (2021) by VRwithAndrew

### VR Rendering Issues
- [UNITY Aliasing FIX, Jaggy Noisy Blinking edges in VR URP](https://www.youtube.com/watch?v=_fKaESkzPT0) (2024) by NikoVR
- [Flickering in Unity VR: Fix Flickering and Pixel Noise on Edge](https://www.youtube.com/watch?v=Lls93SG94Os) (2023) by Roadway VR
- [Behind the Scenes of ‘COMPOUND,’ a New Hardcore Rogue-Lite VR FPS](https://developer.oculus.com/blog/compound-rogue-lite-vr-fps/) (2022)
- [MSAA + 3D Widgets = Horrible jagged edges](https://forums.unrealengine.com/t/msaa-3d-widgets-horrible-jagged-edges/138040) (2020) in UE Forums
- [How to improve visual rendering quality in VR](https://www.youtube.com/watch?v=wyUfZpz4Aw8) (2019) by Ryan O’Shea
- [Common Rendering Mistakes](https://developer.oculus.com/blog/common-rendering-mistakes-how-to-find-them-and-how-to-fix-them/) (2019) by Trevor Dasch
- [Anti-aliased Alpha Test](https://bgolus.medium.com/anti-aliased-alpha-test-the-esoteric-alpha-to-coverage-8b177335ae4f) (2017) by Ben Golus
- [Steps to Avoid Aliasing in VR](https://news.ycombinator.com/item?id=12183340) (2016) by John Carmack

### Others
- [The Ultimate XR Developers Resource Guide](https://github.com/authorTom/ultimate-XR-dev-guide) by authorTom
- [New World Notes](https://nwn.blogs.com/) by Wagner James "Hamlet" Au

## Networking / Multiplayer
```
"People come to The Oasis for all the things they can do, 
but they stay because of all the things they can be."

- Wade Watts, Ready Player One (2018) - 
```
- [Beej's Guide to Network Programming](https://beej.us/guide/bgnet/html/) (2025) by Brian Hall
- [Choosing the right network model for your multiplayer game](https://mas-bandwidth.com/choosing-the-right-network-model-for-your-multiplayer-game/) (2024) by Glenn Fiedler
- [The Ultimate Guide to Forwarding Ports in Your Router](https://portforward.com/how-to-port-forward/) (2021) by Jason Bauer
- [The Loner: Why Some People Play MMOs Alone](https://www.youtube.com/watch?v=b2l2ZxNhCSg) (2018) by Damion Schubert
- [Netcode 101 - What You Need To Know](https://www.youtube.com/watch?v=hiHP0N-jMx8) (2017) by Battle(non)sense
- [Gaffer On Games Articles](https://gafferongames.com/) by Glenn Fiedler
- [BaaS + Game Server Comparison Sheet](https://docs.google.com/spreadsheets/d/1x0eok6EZzigar_K3QNdzTYNhp5NLywLGqBuopKiVzao/) by Imperium42
- [Multiplayer Networking Resources](https://github.com/0xFA11/MultiplayerNetworkingResources) on GitHub
- [Más Bandwidth](https://mas-bandwidth.com/) articles
- [Development and Deployment of Multiplayer Online Games](http://ithare.com/contents-of-development-and-deployment-of-massively-multiplayer-games-from-social-games-to-mmofps-with-stock-exchanges-in-between/) (2015) by No Bugs Hare

## Artificial Intelligence
- [Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) by 3Blue1Brown
- [Intro to Large Language Models](https://www.youtube.com/watch?v=zjkBMFhNj_g) (2023) by Andrej Karpathy
- [Neural Networks: Zero to Hero](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) by Andrej Karpathy
- [llama3 implemented from scratch](https://github.com/naklecha/llama3-from-scratch) (May, 2024) by Nishant Aklecha
- [AI Canon](https://a16z.com/ai-canon/) (May, 2023)
- [The Rise of the AI Engineer](https://www.latent.space/p/ai-engineer) (Jun, 2023) by swyx &amp; Alessio. Followed by [Rise of the Planet of the AI Engineer](https://www.latent.space/i/143067206/rise-of-the-planet-of-the-ai-engineer) (Mar, 2024) in Latent Space
- [LLM-Sampling](https://artefact2.github.io/llm-sampling/index.xhtml)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [Comprehensive Guide to Chain-of-Thought Prompting](https://www.mercity.ai/blog-post/guide-to-chain-of-thought-prompting) by Maithili Badhan
- [Advanced Prompt Engineering Techniques](https://www.mercity.ai/blog-post/advanced-prompt-engineering-techniques) by Maithili Badhan

### Generative AI
- [Microsoft Generative AI for Beginners](https://github.com/microsoft/generative-ai-for-beginners)
- [Generative AI Handbook](https://genai-handbook.github.io/#) (June, 2024) by William Brown
- <https://generativeai.pub>
- [Every Way To Get Structured Output From LLMs](https://www.boundaryml.com/blog/structured-output-from-llms) (May, 2024) by Sam Lijin

### Publications
- [Good AI Podcasts and Newsletters](https://github.com/swyxio/ai-notes/blob/main/Resources/Good%20AI%20Podcasts%20and%20Newsletters.md) by swyx

## 3D Environment Art
```
"Art is never finished, only abandoned. "

- Leonardo da Vinci -
```
### Polycount Wiki
The [Polycount Wiki](http://wiki.polycount.com/wiki/Polycount) is "a catalog of information aimed at game development artists; whether professional, student, or hobbyist." To be honest, this is the only resource you need if you're starting out as a 3D Game Artist. It covers all the topics. Don't be fooled by the old-school UI. This is the place where the AAA game artists hang-out. I'll try and hand-pick a couple of links which are pertinent to 3D environment art:

### Environment Art Theory
- [Environment art isn't about 'making pretty things'...so, what's it about?](https://www.gamasutra.com/view/news/300314/Environment_art_isnt_about_making_pretty_thingsso_whats_it_about.php) (2017) by Jason Hickey
- [Color in games: An in-depth look at one of game design's most useful tools](https://www.gamasutra.com/blogs/HermanTulleken/20150729/249761/Color_in_games_An_indepth_look_at_one_of_game_designs_most_useful_tools.php) (2015) by Herman Tulleken
- [The Aesthetics of Game Art and Game Design](https://www.gamasutra.com/view/feature/185676/the_aesthetics_of_game_art_and_.php) (2013) by Chris Solarski
- [Applying the Elements of Design and Principles of Design in Level Art](https://www.gamasutra.com/blogs/JeremyPrice/20110318/7258/Applying_the_Elements_of_Design_and_Principles_of_Design_in_Level_Art.php) (2011) by Jeremy Price

### Concept Art
- [Concept Fundamentals](http://wiki.polycount.com/wiki/Concept_Fundamentals)
- [FZD School of Design videos](https://www.youtube.com/user/FZDSCHOOL/videos) by Feng Zhu

### 3D Modeling
- [Topology](http://wiki.polycount.com/wiki/Topology)
- [Subdivision Surface Modeling](http://wiki.polycount.com/wiki/Subdivision_Surface_Modeling)
- [Vertex Normal](http://wiki.polycount.com/wiki/VertexNormal)
- [Topology Guides](https://topologyguides.com/) by Johnson Martin

### Texturing
- [Environment Texturing Tutorials](http://wiki.polycount.com/wiki/Environment_Texturing)
- [Texture Coordinates](http://wiki.polycount.com/wiki/Texture_Coordinates)
- [Channel Packing](http://wiki.polycount.com/wiki/ChannelPacking)
- [Multi-Texture](http://wiki.polycount.com/wiki/MultiTexture)
- [Photogrammetry Thread](https://polycount.com/discussion/140949/photogrammetry-thread) (2014 to present) by littleclaude

### Normal Maps
- [Normal Map](http://wiki.polycount.com/wiki/Normal_map)
- [Texture Baking](http://wiki.polycount.com/wiki/Texture_Baking)
- [A Practical Guide on Normal Mapping for Games](http://polycount.com/discussion/146667/a-practical-guide-on-normal-mapping-for-games) (2015) by Alexey Oshchepkov a.k.a. Superfranky
- [Of Bit Depths, Banding and Normal Maps](https://polycount.com/discussion/107196/youre-making-me-hard-making-sense-of-hard-edges-uvs-normal-maps-and-vertex-counts) (2015) by Joe "EarthQuake" Wilson
- [Skew you buddy! Making sense of skewed normal map details.](https://polycount.com/discussion/147227/skew-you-buddy-making-sense-of-skewed-normal-map-details) (2015) by Joe "EarthQuake" Wilson
- [You're making me hard. Making sense of hard edges, uvs, normal maps and vertex counts](https://polycount.com/discussion/107196/youre-making-me-hard-making-sense-of-hard-edges-uvs-normal-maps-and-vertex-counts) (2012) by Joe "EarthQuake" Wilson
- [Understanding averaged normals and ray projection/Who put waviness in my normal map?](https://polycount.com/discussion/81154/understanding-averaged-normals-and-ray-projection-who-put-waviness-in-my-normal-map) (2011) by Joe "EarthQuake" Wilson

### Lighting & Rendering
- [Lighting Resources](http://wiki.polycount.com/wiki/Lighting)
- [An In-Depth Look at Real-Time Rendering](https://www.unrealengine.com/en-US/onlinelearning-courses/an-in-depth-look-at-real-time-rendering) (2019) by Sjoerd de Jong
- [Unreal Engine 4 Lighting Academy](https://www.youtube.com/user/51Daedalus/playlists) by 51Daedalus

### Physically-Based Rendering
- [Basic Theory of Physically-Based Rendering](https://marmoset.co/posts/basic-theory-of-physically-based-rendering/) by Jeff Russell
- [Physically-Based Rendering, And You Can Too!](https://marmoset.co/posts/physically-based-rendering-and-you-can-too/) by Joe "EarthQuake" Wilson
- [PBR Texture Conversion](https://marmoset.co/posts/physically-based-rendering-and-you-can-too/) by Joe "EarthQuake" Wilson

### Modular Environments
- [Modular Design &amp; Workflow](http://wiki.polycount.com/wiki/Modular_environments)
- [Creating Trim Textures 4 Part Free Tutorial - Step by Step](https://www.artstation.com/pixelmasher/blog/1zja/creating-trim-textures-4-part-free-tutorial-step-by-step) (2019) by Tim Simpson

### Landscapes & Foliage
- [Terrain Modeling and Texturing](http://wiki.polycount.com/wiki/Landscape)
- [Environment Scupting - Sculpting Tiled Maps](http://wiki.polycount.com/wiki/EnvironmentSculpting)
- [Foliage Tutorials](http://wiki.polycount.com/wiki/Foliage)
- [Grass Technique](http://wiki.polycount.com/wiki/GrassTechnique)
- [Vertex Color](http://wiki.polycount.com/wiki/Vertex_color)

### Optimization
- [Polygon vs. Triangle vs. Vertex Count](http://wiki.polycount.com/wiki/Polygon_Count)
- [GPU Performance for Game Artists](http://fragmentbuffer.com/gpu-performance-for-game-artists/) (2017) by Keith O'Conor
- [Polycount vs Vertex count](https://distantsoulsdev.blogspot.com/2013/02/polycount-vs-vertex-count.html) (2013) by Matías Nazareth Goldberg

### Technical Studies and Research
- [Game Art Tricks](https://simonschreibt.de/game-art-tricks/) by Simon Schreibt
- [Graphics Studies Compilation](http://www.adriancourreges.com/blog/2020/12/29/graphics-studies-compilation/) (2020) by Adrian Courrèges
- [Interesting Research](https://polycount.com/discussion/136458/interesting-research-thread) Thread (2014-2020) by littleclaude

### Career Advice
- [Freelance](http://wiki.polycount.com/wiki/Freelance)
- [Game Industry Tips](http://wiki.polycount.com/wiki/Game_Industry)
- [8 Tips for Artists Struggling With Motivation](https://www.polygon-academy.com/tips-for-artists-struggling-with-motivation/) (2018) by Tim Simpson
- [10 Insider Tips for Digital Artists Applying to Game Studios](https://www.polygon-academy.com/10-insider-tips-for-artists-applying-to-game-studios/) (2018) by Tim Simpson
- [WHY Your portfolio needs to be on ArtStation](https://www.polygon-academy.com/why-your-portfolio-needs-to-be-on-artstation/) (2018) by Tim Simpson
- [The Death of Curiosity](https://polycount.com/discussion/171153/the-death-of-curiosity) (2016) by Joe "EarthQuake" Wilson

## Blender Addons
- [Blender To Unity FBX Exporter](https://github.com/EdyJ/blender-to-unity-fbx-exporter)

## CC0 Assets
- [OpenGameArt](https://opengameart.org/) filter by license
- [Kenney](https://kenney.nl/)
- [Free Casual Game Sounds](https://dustyroom.com/free-casual-game-sounds/)
- [Screaming Brain Studios](https://screamingbrainstudios.com/)