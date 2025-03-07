# Copy another software

I'd avoid bluntly calling to copy a proprietary software. That's potential for troubles (see [this post](https://devtalk.blender.org/t/copyright-guidelines-for-devtalk/17331?u=l0lock) for more context on that), and in the first place it doesn't make a good feature proposal since it assumes that both community members and developers are already familiar with what you refer too, which you can't guarantee.

Apart from potential legal implications, software is built to serve specific needs, making direct comparisons between different types problematic. `A 3D content creation tool like Blender cannot be optimized to perform like a game engine, replicate the capabilities of painting software, or function as an IDE. Such cross-comparisons are limited by the distinct requirements and constraints of each type of software.`

And to begin with, we don't really have to "copy" anything or add new systems, we can also just make our current tools better. Which is also simpler to implement and maintain.

----

Instead, I would advise you to flesh out your proposal so that anyone can understand the idea and its potential benefits, and developers passing by should also be able to assess its feasibility without needing to conduct extra research.

Start by describing the current need:

- **What’s lacking in Blender?** `For example, you mentioned the value graph become too cluttered with many keyframes, but can you detail that?`
- **How are current solutions falling short?** `Our current graph already have quite a few ways of filtering keyframes to avoid cluttering, in which way do they not answer your need?`
- **What’s the impact?** Highlight how this limitation affects your animations or workflow.

Then, outline potential solutions:

- **What feature(s) could solve these specific problems?** What it is, what it does, how... 
- **Why is it better?** Compare the proposed feature to Blender’s current tools, explaining how it would improve usability or outcomes.
- **Integration and usability:** Suggest how this could fit into Blender’s existing interface and workflows, perhaps as a toggle in the Graph Editor.
- **Mockups or examples:** If possible, create a visual example of how this could look and work in Blender.

# Edit your message or mark it Done

If that's what you are looking for, please [edit](./edit) your proposal to set its status as "Done", otherwise still [edit](./edit) your post to explain why this solution isn't making it for you, and what would be needed from there to make it work.

# "Make it better" isn't a valid feature proposal

Proposals like "make it better, faster, or use a better algorithm" don’t provide actionable information for developers. They’re already committed to improving Blender's performance and features, but without specifics, such posts offer no guidance on **what** to improve or **how** to do it.

A strong proposal should clearly outline **what is lacking, why it’s an issue, and how it could be improved.** This allows developers to immediately understand the problem and assess if a solution is feasible. Concrete examples definitely help to contextualize the proposal:

- What is slow or inefficient?
- What specific tools, workflows, or processes are problematic?
- How does it impact your projects or goals?

```
EXAMPLES

⸻For example, instead of saying 'faster simulation,' describe a scenario: 'Fluid simulations with high viscosity take excessively long on 4K meshes; optimizing this could save hours during iterations.'
⸻What **exactly** feels unintuitive about Blender’s material workflow? What specific features or changes do you think are needed? Without these details, it’s hard to even understand the problem, let alone determine how to address it.
```

If you can’t pinpoint the issue or solution, it’s better to seek community feedback or provide detailed examples rather than post vague requests.

# Not a feature proposal

Hello, Welcome to RCS.

This platform is meant for posting and discussing feature proposals for Blender. To get support about Blender, please use other platforms, such as [Blender Artists Community](https://blenderartists.org/) or [Blender Stack Exchange](https://blender.stackexchange.com/).

# Yup isn't "the" standard

Blender just uses one of [four standards](https://blender.community/c/rightclickselect/nRBY/?sorting=hot#comment-59616).
