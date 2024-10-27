# Research & background

Progress tracking [here](checklist.md)

> [!IMPORTANT]
> Image uploads are coming, but I'm probably doing 90% of the work in the holidays.

## Background & purpose

### Context

Often a niche and relatively obscure genre, rhythm games have their own unique allure that draws a specific kind of gamer. With keyboards being effectively a native control and input source, it surely wouldn't be surprising that the race for performance becomes a hardware development race not unlike Formula 1; the hardware race is arguably the biggest driver of performance now, far surpassing that of natural improvement even in top players. Indeed, manufacturers like [Wooting](https://wooting.io) that were early to the now surging trend of hall effect analog keyboards and switches have now dominated the market, by far being the industry leader in software and hardware. With capitalism, however, comes variety, or rather, the lack thereof. This isn't unusual, given its only sensible to commercialise and continue the products that bring in the most revenue and attention, even if the project has genuine merit and purpose. However, as a somewhat regular player of these games and knowing friends that frequent these games, I've always felt there's been something missing. The custom experience. Unique, tailored, perfect, just to our specifications.

### Purpose

There is one purpose with this product: to provide uncompromising performance when playing these rhythm games, and to be fully customisable. We need a design that's both approachable for beginners and experts alike, without sacrificing quality or usability; the product should be designed without planned obsolescence or unsustainable practices in mind, instead being built for the user - extensible, modifiable, and recyclable or reusable at the end of its lifespan. While these are a brief outline of some details the product should fulfil, many more specifics can only be decided after an iterative design process. At the end of the day, the product is just a keyboard with a specific layout, but an extremely good one at that.

### Considerations

> [!NOTE]
> These are here by convention although much more of the standard format will be substituted for the double diamond design process

Of course, as a school project, there are time limitations among a slew of other things to consider - a few are listed here:
| Consideration | Justification |
| :---: | --- |
| Time | The proposed timeline for the project is 13 weeks - holidays included; project tracking and management will eventually be listed in an infographic (kanban/gantt) and pasted somewhere here. These time constraints are evaluated for the project based on other considerations mentioned here, providing a step-by-step outline for when something should be done and what should be done at any given point. |
| Cost | While there isn't a specific cost cap for this project, common sense should be applied to any spending for the project to maintain a "reasonable" level of realism for the project. Overbudget projects are undesireable for a variety of reasons, and being overbudget isn't a great look for the financial sustainability of the project, particularly when commercialising a product. |
| Tools | An understanding of available and feasible tooling should be a no-brainer for any self-respecting engineer, and given the outsourced nature of production and manufacturing for this project, industry standards should be applied to this project no less than they would be for a commercial version. A few reasons for this: designs can be physically impossible to manufacture, they can be highly convoluted and inefficient, etc. |
| Materials | Once again due to the outsourced materials, the only restrictions on material are external manufacturing limitations and the prohibitive cost of certain materials. However, cost shouldn't be the only reason various materials are considered; material strength, longevity, and comfort combined with manufacturing ease are all major factors when considering the specifications of a design. |
| Skills/Prior knowledge | A good knowledge of CAD and CAM/CNC is preferrable here not only maintain a common ground of skill but also to establish an understanding of the design process and its principles, where understanding the choices made in any given design would facilitate making the right choice in this design. |

## Research

### Areas of Investigation

| Area | Relevance |
| :---: | --- |
| Analysis of existing designs | Understanding common pitfalls and designs allows for not only a more streamlined design process better directed towards the design specifications, but also a more complete understanding of the project insofar as to remove much of the time-intensive components - iterative design is less necessary when a product has largely been "solved" by companies with more money. |
| Materials & tech | Understanding *how* something works is arguably one of the most, if not the most essential component of any project - material choice, tooling, designing for either of the above - all of these hinge on understanding every component of the project. |
| Tools | Tooling and machinery is often the biggest restriction to the specifications of a project, given the limitations of CAD software far exceed reasonable manufacturing standards - something can be a valid design, bar the fact that it'd be impossible to create without technologies such as SLS (selective laser sintering) that are often inaccessible or create unavoidable drawbacks that may invalidate the design. Of course, safety standards would also be greatly improved by an understanding of the tools used in any project, where workplace safety is often of the utmost importance in any studio. |
| Construction | While the "build" segment of the project may seem less prominent than the design and engineering behind something, it's also the moment all the design considerations and criteria are validated. Understanding the construction of a project would also allow engineers and designers to optimise their designs for repairability and usability. |

### Materials & technologies

| Material | Notes |
| :---: | --- |
| Aluminium | One of, if not the most versatile material in modern engineering, aluminium is found in a variety of applications not only for its excellent cost-effectiveness, but also for its ease of manufacturing and abundance in nature - being one of the most common elements, it's an accessible entry point into metallic products. Additionally, its ease of access in today's age of online manufacturing makes it especially suitable for this project, balancing quality with reasonable affordability. |
| Titanium | In comparison to aluminium, titanium features excellent mechanical properties and durability, the only limiting factor being its difficulty of manufacturing and it's prohibitive cost. However, providing approximately double the strength of aluminium, it may be used in the final product to varying degrees, largely to extend the lifetime of the product by nature of its increased mechanical durability. |
| ABS | Cheap, easy to manufacture, and widespread, ABS plastic is another material of choice when it comes to mass production, its only limiting factors being its low melting point and poor durability against solvents and UV exposure. However, this isn't likely to affect this project as it isn't being designed for outdoor use or intended for these environments where this would be a legitimate concern. |
| Nylon | Nylon is an extremely durable polymer, being waterproof and lightweight as well as innately fire-resistant. Formulas are also easy to tune for desirable characteristics, whether that be chemical resistance or weatherproofing. Its self-lubricating nature is also desireable in its use as an engineering material, being able to replace metal in many cases. |
| PLA | PLA is arguably the most common filament used in FDM 3D printing, being organically derived as well as cheap, making it a highly desireable prototyping material. Additionally, the rapid prototyping that PLA and 3D printing removes much of the undesireable aspects of iterative design, namely the expensive and time-consuming nature of testing and remaking parts, often hundreds of times. |
| PBT | PBT is much like ABS and PLA in its widespread adoption and excellent mechanical properties, but provides much more durability for the same product. An example of this would be keycaps for this project, where PBT keycaps are much more wear-resistant, UV-resistant, and overall much more durable compared to ABS, albeit more expensive, and substantially more suitable for a final product compared to PLA, which should not be used in production. |
| Acrylic | Name brand Perspex, acrylic is typically used in place of glass when a clear material is required. In this case of this project, it'll be considered as an optional top or bottom plate, allowing for a better aesthetic through exposing the inner circuitry. |

| Tech | Notes |
| :---: | --- |
| SLS printing | Selective laser sintering is another popular method of 3D printing which may be used for complex geometries typically unachievable even by multi-axis CNC machines and FDM printers. Some benefits typically associated with this method include its low cost-per-part at high volumes, as well as its excellent versatility when it comes to material choice - titanium, aluminium, nylon - all are valid choices for SLS. Perhaps the only barrier to entry for hobbyists and small companies would be its prohibitively high opportunity cost, even non-industrial solutions designed for the public costing upwards of 5 figures. |
| FDM printing | This is likely what people think of when they hear "3D printing", being the most commonly adopted solution among the general public. While it may be comparable in speed to other 3D printing techniques only on single parts, FDM quickly falls off in part durability and complexity when more straining designs are necessary, rendering it only suitable for small-volume productions or prototyping. Options like the MarkForged series of FDM printers exist, but those are far beyond the average consumer price, reaching far into the 5 figure range and beyond. |
| SLA printing | SLA is another modern technique for 3D printing, utilising a high-definition UV displays to selectively cure UV resins and producing extremely precise parts with the caveat of much more restrictive material options. While metallic resins and their processing methods exist, they're often not without disqualifying flaws such as their poor tolerances or general lack of durability. |
| CNC machining | CNC machining is perhaps the most important development to modern manufacturing, allowing for complex geometries otherwise not feasible for a human operator to create to be easily mass produced. However, CNC can also be incredibly restrictive and unforgiving to the operator, demanding programs that not only conform to tool limitations but requiring painstaking optimisation should any semblance of efficiency be desired. |
| PCB printing | PCBs are practically everywhere in modern electronics, and the ability to custom print any PCB just as you would any other part of the project has come to be expected in modern engineering. Indeed, custom PCBs would make up most of the engineering difficulty of this project, making this technology an essential part of quick turnarounds in part engineering. Functionally though, these printers are just laser engravers, etching away the unwanted areas of copper to form the desired traces. |
| Hall effect sensors | Hall effect (HE) sensors function on the basis of electromagnetism, utilising the inherant magnetic field of electrons to detect external magnetic fields present around the sensor. To that effect, HE sensors allow for contactless analog input, a highly desireable function for this project and many other technologies we take for granted; ignition timing, door sensors etc. all rely on HE sensors to function. |
| Signal Multiplexers (MUX) | A specific piece of hardware for a specific purpose - reducing the number of I/O interfaces necessary for any components. While the naive approach to electronics would assign each interface independently, MUXs allow for multiple inputs to be read to a single I/O, greatly increasing the interface potential for a project. |
| Microcontrollers (MCCs) | Not to be conflated with CPUs, MCCs are a complete package of the former, hardware and software interface all inclusive. Conversely, CPUs and microprocessors aren't designed to function independently of their driver hardware, necessitating further integration compared to their MCC counterparts. |
| LEDs | LEDs are almost ubiquitous in the world of hardware design, their light being utilised for anything from purely aesthetic to critically functional. Similarly, they find purpose in this project both for aesthetic purposes and as indicator lights, allowing for a much more streamlined user experience. |

### Tools

| Tool | Notes |
| :---: | --- |
| Soldering iron | As with any electronics project, a soldering iron is essential to even assemble the PCB and its components if not pre-assembled from the manufacturer. While varieties exist for the intricacies of the trade such as micro-soldering as well as specific desoldering irons, it's arguably more important to have one at all, seeing as assembly would be impossible without. While it's preferred that ventilation is available whenever soldering indoors, a respirator or similar mask is also acceptable. |
| Alligator clips | These are part of the soldering toolkit, holding parts in place for ease of access to different areas and better soldering angles. These typically also come with a stand, allowing magnifiers and other components to be mounted on the various arms for an ergonomic workflow. |
| Microscope/Magnifier | Mounted on the clip stand, or independently located on the workbench, these devices allow for exponentially greater accuracy when soldering and positioning parts, streamlining the process as well as increasing the ease of inspection and quality control. While not serving much purpose independently, they contribute to the engineering workflow to alleviate much of the stress that comes with working on these parts. |
