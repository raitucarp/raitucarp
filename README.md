
# I'm Ribhararnus Pracutiar

Hi there,

I've been in the programming world since around 2007. Focusing mainly on JavaScript/TypeScript on the frontend side (Next.js, React, React Native, Node.js in various runtimes), and TypeScript and Go on the backend. Occasionally, I work with Python or Rust when the situation calls for it.

I am currently Open to Work.

# How I write code

In the past few years, the wave of vibe-coding and automated AI usage has grown stronger. I take a slightly different position. I write code like an artist preparing brushes, paint, and canvas. Not merely to complete tasks, but to build a relationship between structure, meaning, and readability. I am open to using AI for exploration and analysis, especially in prompt engineering, but when composing core code, I prefer a slow, mindful, and measured craftsmanship.

My journey with prompt engineering has also been quite long. I draw from semiotics, linguistics, and conlang to design small languages that assist annotation and thinking models. One example of exploration I've done is designing a note-taking language that can transform the meaning of text into syntactic or symbolic form. Some of these experiments were supported by AI models, which I used as a sparring partner for ideas.

Maybe one day I'll write about those in more detail, in the form of blog essays or public notes.

For now, I'd like to show several projects that I am currently working on or have worked on in the past, so you can get a sense of how I work, think, and assemble things from zero.

# Ongoing Projects

### gomix ([github.com/raitucarp/gomix](github.com/raitucarp/gomix))

Status: WIP (v0.0.3x)

The situation is simple. I want the experience of writing frontend in Go to feel more natural, integrated, and with minimal context switching. I don't quite fit with Go's built-in html/template. At the same time, I like how React removes the boundaries between HTML, CSS, and JavaScript through JSX. That approach isn't merely technical. It's about aligning semantics.

The question arising: Can such an approach be applied in the Go ecosystem?

I began working on gomix as an answer to that question. Its primary focus is DX engineering. I want a UI syntax for Go that is consistent, pleasant to work with, and reduces mental load when switching between view representation and logic. There is inspiration from Zed editor's gpui, and also from component design systems like ChakraUI.

Long-term goal: UI HTML, WebView, and desktop-native renderers that share the same syntactic language.

The process is ongoing. I move slowly because this project requires a clean foundation.

### epub ([github.com/raitucarp/epub](github.com/raitucarp/epub))

Status: Ready for use, prior to official v1.0.0 release

Here, the context is different. I wanted to translate the W3C EPUB technical standard into a truly functional Go implementation. The process is not as simple as reading code examples. I had to read the specification, understand it, and reassemble each part into functions that other people can reasonably use.

The initial purpose was personal. I was preparing an EPUB reader application with a fairly radical UI approach. For that, I needed a foundational library that was strong and controlled. The existing Go EPUB libraries at the time didn't fit my needs.

The result is this library. There is still room for refinement, but the foundation for reading and writing EPUB works and can be adopted.

### openlibrary-go ([github.com/raitucarp/openlibrary-go](github.com/raitucarp/openlibrary-go))

Status: Pre-release (v0.1.1)

When working on the EPUB library, I encountered a frequent situation: metadata in some EPUB files is incomplete or broken. The W3C document does not solve this issue because it only defines the format, not the content.

The question that emerged: Where does one retrieve the missing information?

The answer is third-party APIs. I then built an OpenLibrary API wrapper for Go. Much of its documentation is implied and not always directly usable, so I had to build my own understanding of their data response patterns.

The next step is to report the existence of this library to OpenLibrary as an unofficial option.

Other projects (active at various points between 2020–2024)

- raitui: GUI framework based on raylib for Go. Halted due to text rendering and shader limitations.
- wordxkit: A web-based dictionary application built on WordNet, with embeddings, vector database, GraphQL, PostgreSQL, pattern-based lexicon, and semantic play.
- leksikon: A localized Indonesian version of wordxkit using Neo4J and a large lexicon dataset.
- HN reader: Several desktop applications experimenting with real-time reactivity.
- scrolls: A reading app with a structural reading approach, unreleased.
- and many more... (at least 10+ projects)

Most of these projects were not published for both technical and non-technical reasons. But each of them contributed to the foundation of how I think about systems, data representation, and reading as a cognitive activity.

### Closing

If you are a recruiter or a representative of a team, I am open to discussion. I can explain my working approach, how I make design decisions, and what I learned from projects that did not end in public release.

Outside of programming, I read a lot of philosophy, science fiction, and experimental books, and I'm something of a digital bibliophile. I also still maintain the desire to write books and draw.

Thank you for reading to this point. If you'd like to reach out, I welcome both technical and conceptual conversations.
