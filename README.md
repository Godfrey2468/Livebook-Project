# Livebook-Project
 LIVEBOOK AND ITS POWER.

Scoping Document.

In this project, an overview of Livebook is given and later on an in-depth walk-through.
Livebook is a web application for writing interactive and collaborative code notebooks, just as Jupyter notebook works with Python. Livebook and its features work well with Elixir and beam to best bring out the core elixir features. It is powered by [Nx](https://www.youtube.com/watch?v=fPKMmJpAGWc&ab_channel=CodeSync). The Livebook GitHub Repo has a well documented installation guide that can be found [here](https://github.com/livebook-dev/livebook)

[Elixir New Features 0.7](https://www.youtube.com/watch?v=lyiqw3O8d_A&list=PLezCyUgorHVYR-M80A8rIx0fwy4E61RBE&index=2&ab_channel=Livebook) Please note at the time of writing the latest version is 0.10 according to the Livebook Github Repository.

Some of the Livebook features that will be learned during the demonstration include but not limited to;

1 Markdown Support

2 [Inline Documentation and code formatting](https://fly.io/blog/livebook-for-app-documentation/)

3 [Interactive results such as tables , data visualization and maps](https://www.youtube.com/watch?v=U6nuPjyAUPw&ab_channel=Livebook)

4 [Automation using Smart cells](https://www.youtube.com/watch?v=4hVIxyHxwK8&ab_channel=ElixirConf)

5 [Collaboration with multiple users](https://youtu.be/EhSNXWkji6o?list=PLezCyUgorHVYR-M80A8rIx0fwy4E61RBE&t=538)

6 [Livebook Intergrations such as Kino](https://livebook.dev/integrations/)

The elixir features to be demonstrated in this project via livebook could also be considered as the benefits of using Elixir, they are well defined in the [Elixir-Lang website](https://elixir-lang.org/) and they include;


1. Scalability - an application program would be scalable if it could be moved from a smaller to a larger operating system and take full advantage of the larger operating system in terms of performance (user response time and so forth) and the larger number of users that could be handled.
This is seen on the portability and being able to version control .livemd files, even using third party applications such as GitHub.

2. [Concurrency](https://youtu.be/xF-_goFLaFo?t=43)  -  the ability to perform two or more tasks apparently at the same time.
This is demonstrated by being able to run multiple nodes that use Elixir BEAM on Livebook . The teaming feature unfortunately is still under development. Bidirectional live counter is one good example.

3. [Fault- tolerance](https://fly.io/blog/livebook-for-app-documentation/) - Elixir has built-in support for fault tolerance, including features like supervision trees and fault-recovery mechanisms. Livebook does support supervision and child processes using Kino.

4. [Functional Programming](https://www.youtube.com/watch?v=HjEHtM0XQU8&ab_channel=UnderjordbyLarsWikman) - this will be a simple code snippet showing Elixir’s functional programming and the output.


5. Erlang compatibility - You can directly code Erlang on Livebook side by side with Elixir and this will be demonstrated by a  simple piece of code in both erlang and Elixir.

6. [OTP Distribution](https://www.youtube.com/watch?v=P0WJBP2bzuk&ab_channel=Beambasket)- Elixir allows us to communicate across these nodes via a few different mechanisms, this is equally possible in Livebook and can be demonstrated using a portal game


By the end of the project should be a clear understanding of,
- Elixir core features implemented on Livebook
- Process and OTP handling in Livebook
- How ecto is integrated using Kino
- Data visualization using Mermaid and VegaLite.
- Nodes concurrency and key application data.

A list of tutorials, websites, repositories and videos  used to explain  Live book and its power will be included for any future references needed.

Websites Used
-
1. [Elixir-Lang website](https://elixir-lang.org/)
2. [Elixir-Hexdocs](https://hexdocs.pm/elixir/Kernel.html)
3. [Fly.io Blog on Livebook](https://fly.io/blog/livebook-for-app-documentation/)

Videos Used
-
1. [Youtube Official Livebook page](https://www.youtube.com/@livebookdev/videos)
2. [Introducing Nx](https://www.youtube.com/watch?v=fPKMmJpAGWc&ab_channel=CodeSync)
3. [Functional Programming](https://www.youtube.com/watch?v=HjEHtM0XQU8&ab_channel=UnderjordbyLarsWikman)
4. [Automate and Learn smart Cells](https://www.youtube.com/watch?v=4hVIxyHxwK8&ab_channel=ElixirConf)

GitHub Repos
-
1. [Livebook Repository](https://github.com/livebook-dev/livebook)
2. [Numerical Elixir Repository](https://github.com/elixir-nx/)
3. [Kino Ecto Repository](https://github.com/vorce/kino_ecto)
