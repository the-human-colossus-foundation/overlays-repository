# Overlays Repository

Welcome to the Overlays Repository, a community-driven project to develop and share task-specific overlays for the **[Overlays Capture Architecture](https://oca.colossi.network) (OCA)**. This repository allows contributors to create, share and find overlays that extend and improve the functionality of Capture Bases and other overlays. This is achieved by providing documentation and overlay definitions [.overalyfile](https://oca.colossi.network/specification/overlayfile).

## What is Overlayfile?

The OverlayFile is a custom, domain-specific language that allows you to create a definition of any given overlay programmatically. See the [Overlayfile specification](https://oca.colossi.network/specification/overlayfile) for more information.

## Core Overlays

The [OCA Specification](https://oca.colossi.network/specification/) defines 13 distinct overlays as a baseline for anyone who would like to build their own semantic stack. You can find the definitions of these overlays in the [core.overlayfile](/core.overlayfile).


## What is an Overlay?

Overlays are cryptographically linked objects that provide task-oriented definitional or contextual information to a **Capture Base** or other **Overlays**. These overlays enable users to:

- **Enhance Data with Metadata** – Attach additional descriptive, contextual, or structured information to underlying objects.
- **Define Business Logic** – Implement rules and conditions that influence the behavior of a system interacting with the overlay.
- **Customize Data Presentation** – Structure how data is formatted, displayed, and interpreted for different audiences.
- **Transform User Experience** – Modify and enrich how information is visually and functionally presented to viewers.
- **Automate Processes** – Guide automated agents by defining workflows, actions, or decision-making parameters.
- and more ...

Overlays allow for flexible and structured data enhancement while maintaining a consistent foundation. They play a crucial role in extending the utility of the **Overlays Capture Architecture (OCA)**.

For more information about OCA, visit: [OCA Documentation](https://oca.colossi.network)

---

## Overlays

List of the currently submitted overlays can be found [here](/overlays.md)

---

## Contributing to the Overlays Repository

We welcome and encourage contributions from the community. Follow the steps below to create and submit your overlay.

### 0. Check for Existing Overlays

Before creating a new overlay, check if a similar idea already exists. If an existing overlay addresses the same need, consider improving or extending it instead of creating a new one.
The latest list of overlays can be found [here](/overlays.md)

### 1. Define the Purpose
Clearly define the **goal** of the overlay. Each overlay should serve a **single purpose** and should be focused on solving a **specific** problem.

### 2. Describe the Use Case
Provide a detailed **use case** explaining:
- Where and why the overlay is helpful.
- The scope and intended usage.
- Any relevant contextual framing.
- How the overlay may link to and interact with other overlays to enhance functionality.

This description helps others understand the overlay’s **purpose and potential applications**.

### 3. Create `.overlayfile`

Create definition of your overlay using `.overlayfile`, use tools like [oca-bin](https://github.com/THCLab/oca-bin/releases) to validate it and build few example of `OCAFILE` with it.

Create a definition for your overlay using the `.overlayfile` syntax. Use tools such as [oca-bin](https://github.com/THCLab/oca-bin/releases) to validate it.

### 4. Create an example using the OCAFILE syntax.
Using the [OCAFILE syntax](https://oca.colossi.network/specification/ocafile.html), develop an example that demonstrates the overlay in action. Use tools such as [oca-bin](https://github.com/THCLab/oca-bin/releases).

### 5. Develop a Template
Follow the [standard template](/template.md) structure to ensure consistency across all overlays. Templates help maintain clarity and usability.

### 6. Update [overlays](/overlays.md)

Add new item in the table for community overlay filling all columns.

### 6. Submit a Pull Request (PR)
Push your overlay to this repository by creating a **Pull Request (PR)**.
PR should include
- directory named <NUMBER>-<OVERLAY-NAME>/ in [overlays](/overlays), The number should be next available number from overlays directory.
- `.Overlayfile` definition of proposed overlay following [Overlayfile Specification](https://oca.colossi.network/specification/overlayfile)
- README.md - markdown description of proposed overlay following the [template](/template.md)

---

## Community and Support

Join the community discussions and share your insights! If you have questions or need assistance, feel free to:
- Open an issue or discussion on GitHub.
- Engage in discussions on community forums.
- Reach out via OCA’s official channels [on matrix](https://matrix.to/#/#oca-community:matrix.org).

Let’s build a powerful ecosystem of overlays together!

**Happy Contributing!** 🚀

## License

All work in this repository is under EUPL1.2 License. See [LICENSE](/LICENSE)
