# ChargePath — EV Charging App UI/UX Concept

An AI-assisted student portfolio project by Harsh Vardhan Tomar. ChargePath explores a clearer way for EV drivers to discover compatible chargers, compare station details, and review an estimated charging cost before reserving a slot.

## Open the project

Download this repository and open `index.html` in a modern browser. It is a self-contained file: no package installation, server, API key, or internet connection is required.

Three views are included:

- **Interactive prototype:** search, connector filters, station comparison, booking, confirmation, and cancellation.
- **Design case study:** problem hypothesis, assumed persona, user flow, design rationale, scope, and evaluation plan.
- **Wireframes & system:** three low-fidelity wireframes, reusable components, typography, colors, spacing, and interaction states.

## Design process

1. Frame a concept around charger compatibility, availability, and pricing clarity.
2. Define the journey: discover → compare → reserve → review.
3. Sketch the information hierarchy in low-fidelity wireframes.
4. Build a responsive high-fidelity HTML/CSS/JavaScript prototype.
5. Document a mini design system and a proposed usability-testing plan.

## Implemented features

- Search stations by name or area.
- Filter by CCS2 or Type 2 connector.
- Show connector, charging power, distance, availability, and simulated rate.
- Prevent booking a full station.
- Select date, arrival time, and energy estimate.
- Calculate the estimated cost before confirmation.
- Review and cancel demo reservations within the current page session.
- Handle empty results and invalid dates.
- Provide keyboard focus styles, form labels, text status indicators, and responsive layouts.

## Technology

HTML5, CSS3, vanilla JavaScript, and inline SVG. The prototype contains no external dependencies.

## Validation

Flow-logic checks covered filters, empty results, unavailable stations, charging estimates, booking, cancellation, date validation, and tab selection. These checks used a DOM stub; browser rendering and real-user usability testing have not been verified.

## Project boundaries

This is an **AI-assisted design concept**, created with ChatGPT. Stations, prices, availability, and the persona are simulated or assumed. The design problem has not been validated through interviews. No real payments or reservations are made, and there is no backend or persistent account storage.

No Figma work, conducted user research, measured usability improvement, or production launch is claimed. The usability-testing section is a plan for future evaluation.
