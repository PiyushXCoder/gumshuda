![Gumshuda Cover](assets/gumshuda_cover.png)

# Gumshuda

## Project Status

This project is currently under active development as a "build in public" initiative, built solely by me. I'm continuously working on new features, improvements, and bug fixes. Your feedback is welcome!

Welcome to Gumshuda, a truly unique real-time, collaborative whiteboard experience!

## What is Gumshuda?

Imagine an infinite digital canvas where you and your team can brainstorm, design, and create together, all in real-time, without worrying about connectivity issues or a central server dictating your every move. That's Gumshuda!

Gumshuda is built on **Local-First principles**. This approach means that unlike most collaborative tools, there's no central server dictating the 'official' state of your whiteboard. Instead, *each client* (that's you and your collaborators!) maintains its own complete copy of the document.

## How it Works (The Magic Behind the Scenes)

This might sound a bit unconventional, and it is! But it comes with some powerful advantages. Because each client has its own document copy, you can continue working seamlessly even if your internet connection drops out. Your work is always safe and immediately available locally.

When you and your collaborators are online and exchanging information, Gumshuda employs a clever system to ensure **Eventual Consistency**. This means that even if operations (like drawing a line, typing text, or moving an object) are received in different orders by different people, the system guarantees that *everyone will eventually see the exact same, converged state* of the whiteboard. It's like everyone contributing to a shared story: no matter when you read the latest update, you'll always end up with the complete, coherent version.

### Key Features:

*   **Real-time Collaboration:** See changes from your team instantly.
*   **Infinite Canvas:** Never run out of space for your ideas.
*   **Local-First Design:** Work offline, stay productive, and enjoy immediate responsiveness.
*   **Eventual Consistency:** Relax knowing that everyone will always be on the same page, eventually.
*   **Empowered Clients:** Your device holds the document's state, not a distant server.

Gumshuda is designed to be resilient, fast, and give you complete control over your collaborative experience. Dive in and start creating!