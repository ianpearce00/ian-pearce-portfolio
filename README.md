# ian-pearce-portfolio
Technical portfolio for Ian Pearce with detailed project case studies and resume-ready documentation.

## Adaptive Tricycle

**Role:** Mechanical Design and Fabrication Team Member  
**Organization:** Rutgers A4A  
**Date:** January 2026–August 2027  
**Technologies and materials:** SolidWorks, Arduino, PETG 3D printing, aluminum, PVC, wood, metal bearings, rubber-coated metal cord

### Project overview

The Adaptive Tricycle is an assistive mobility device designed for a four-year-old child with changing mobility and motor-development needs. The design was intended to remain useful as the child grows, with an expected service period extending from approximately age four through age six to eight.

The primary objective was to create a tricycle that balanced safety, adjustability, durability, parental control, and opportunities for independent skill development. The system combined a mechanically adjustable riding platform, multidirectional occupant support, a parental steering override, and an Arduino-based sound-alert system.

### Design requirements

The project requirements included:

- Providing a safe and stable riding platform
- Accommodating the child’s physical growth over multiple years
- Supporting the development of steering and pedaling skills
- Allowing complete parental control when necessary
- Maintaining durability under repeated use
- Providing adjustable pelvic, torso, head, and steering support
- Including an accessible button-activated sound system
- Allowing the child to practice pedaling without moving the tricycle

Because the tricycle was intended for use by a young child, adjustability and user safety were treated as core design requirements rather than secondary features.

### Mechanical design and materials

The tricycle incorporated components made from aluminum, wood, PVC, PETG 3D-printed parts, metal bearings, and rubber-coated metal cords.

SolidWorks was used to design custom components and refine the overall mechanical arrangement. 3D printing enabled rapid prototyping of custom parts and allowed the team to revise component geometry as new fit and usability requirements emerged. Aluminum and PVC were used for structural and control components, while wood was incorporated into the steering-anchor system.

The design emphasized conservative component selection and more-than-adequate safety factors for parts expected to experience significant stress. Formal load or stress calculations were not performed; instead, the team prioritized robust materials, conservative design assumptions, and physical testing of the completed system.

### Adjustable occupant support

The tricycle included multidirectional occupant support intended to keep the child secure while allowing the support system to adapt as the child developed. The support system included:

- A five-point harness
- Adjustable pelvic support
- Torso support
- Head support
- Custom structural bracing
- Adjustable steering-wheel positioning

The cushioning, pelvic supports, and steering-wheel placement were revised after the team identified inaccuracies in the original dimensional information. These changes improved the fit and usability of the tricycle for the actual rider.

### Parental steering override

The parental override system allowed an adult to steer the front wheel directly while continuing to push the tricycle.

The mechanism used rubber-coated metal cords routed through metal bearings. The cords were connected to a wooden steering anchor and extended toward the parental steering bar. When the parent turned the steering bar, the cords transferred the steering input to the front wheel.

This arrangement provided the parent with direct control of the tricycle while preserving the child’s ability to interact with the steering system. The use of bearings reduced friction and helped guide the cords through the steering path.

### Pedaling and motor-skill development

A jack system was added after user feedback to support progressive skill development. The jack lifts the front wheel off the ground, allowing the child to practice pedaling while the tricycle remains stationary.

This feature created a controlled transition between assisted use and independent operation:

1. The child can practice the pedaling motion without traveling.
2. The parent can monitor the child in a stable environment.
3. The jack can be removed from use when the child is ready for mobile pedaling.
4. The child can gradually develop coordination and confidence.

This modification directly connected the mechanical design to the project’s developmental objective.

### Arduino-based sound system

The tricycle also included a button-activated sound-alert system. The system was built around an Arduino and included:

- A user-operated button
- A DFP audio player
- A speaker
- An SD card containing prerecorded sounds

When the button is pressed, the Arduino triggers the DFP player. The player selects and plays a prerecorded sound from the SD card, with sounds selected randomly. This gives the child a simple and accessible method of producing an audible alert.

The system required soldering and wiring the electronic components into the tricycle while maintaining a practical arrangement within the mechanical structure.

### Testing and iteration

The completed tricycle was tested through a combination of physical use and team evaluation. Various members of the club operated and steered the tricycle to assess:

- Steering functionality
- Parental override performance
- Structural stability
- Support-system fit
- Pedaling behavior
- General usability
- Sound-system operation

The team also performed repeated stress and functional testing to identify weaknesses before delivery. Testing and user feedback led to several design changes, including:

- Adding the stationary pedaling jack
- Adjusting cushioning
- Revising pelvic supports
- Changing steering-wheel placement
- Correcting dimensions based on the actual user’s needs

### Engineering challenges and solutions

#### Challenge: Designing for future growth

The tricycle needed to fit a four-year-old child while remaining usable as the child grew.

**Solution:** The team developed adjustable occupant supports, steering positioning, and other interfaces to accommodate changing body dimensions and motor abilities.

#### Challenge: Maintaining parental control without eliminating child participation

The child needed an opportunity to develop steering and mobility skills, but the parent also needed reliable control.

**Solution:** A cord-and-bearing steering override allowed the parent to control the front wheel directly while the child continued to interact with the tricycle.

#### Challenge: Supporting progressive pedaling development

The child needed to practice pedaling before being expected to control the tricycle while it was moving.

**Solution:** The team added a jack system that lifts the front wheel and allows stationary pedaling practice.

#### Challenge: Correcting dimensional inaccuracies

Some initial dimensions did not accurately reflect the user’s actual fit requirements.

**Solution:** The team used physical testing and feedback to revise the cushioning, pelvic supports, and steering-wheel placement.

### Results

The final design provided:

- Adjustable support intended to accommodate several years of growth
- Direct parental steering control
- A five-point harness and multidirectional occupant support
- A stationary pedaling mode for motor-skill development
- An Arduino-based random sound-alert system
- Custom SolidWorks-designed and 3D-printed components
- A mechanically tested and iteratively refined tricycle

### Lessons learned and future improvements

This project demonstrated the importance of designing around the actual user rather than relying exclusively on initial measurements or assumptions. Physical testing and feedback were essential for identifying fit and usability issues that were not apparent during the initial design process.

Future improvements could include:

- Performing formal finite element or analytical load calculations
- Adding documented test loads and acceptance criteria
- Improving weather and impact resistance of exposed components
- Developing a more compact or enclosed steering-override mechanism
- Adding battery monitoring and protected charging hardware
- Creating a formal adjustment guide for caregivers
- Documenting dimensional adjustment ranges for future users

### Recommended supporting visuals

This project would benefit significantly from visual documentation. The strongest images to include are:

1. Full tricycle photograph
2. Annotated system overview
3. Parental override CAD screenshot
4. Adjustable support CAD screenshot
5. Jack-system photograph or CAD screenshot
6. Electronics diagram or wiring photograph
7. Iteration comparison

For the final portfolio, place a concise project summary and the full-tricycle image near the beginning, then use the CAD screenshots and photographs alongside the relevant technical sections. This will make the project easier to understand than relying on text alone.
