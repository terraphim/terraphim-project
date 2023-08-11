type:: [[feature]]
product:: [[Terraphim]]
relatedfeatures:: [[Topical search and article ingestion]]

- Now the user has a knowledge graph enriched with synonyms and related to experts in the field and maybe discovered some issues with the process model (missing inputs or outputs). It is time to map the SEBoK concepts to the SFIA to increase the number of semantic dimensions.
  logseq.order-list-type:: number
- The user returns to Terraphim and selects the single search source "SFIA catalog." The search prompt is the topic name, in our case, "maintenance." In the search results the user sees SFIA skills that have "maintenance" in the description. If the user accepts some skill, he can import the skill entry in his personal knowledge graph from the SFIA catalog:
  logseq.order-list-type:: number
  ![image.png](../assets/image_1689875267814_0.png){:height 898, :width 711}
- It is basically plain importing from the CSV, but as Logseq attributes require single lines of text, all entries should be transformed into strings. Once the user adds the new SFIA skill he puts a hierarchical backlink (skill categor / skill name) into the frontmatter of a topic:
  logseq.order-list-type:: number
  ![image.png](../assets/image_1689875594772_0.png){:height 713, :width 711}
- Now everything is ready for the user to generate the role's graph that matches the topic. For this particular case, it will be the "system maintenance" role that we will create using the VerbNet ontology of role with [improvements proposed](http://www.meteck.org/files/FOIS23positionsCRC.pdf) by M. Keet.
  logseq.order-list-type:: number
  ![image.png](../assets/image_1689919930406_0.png)
- **Actor** - Participant that is the instigator of an event. - Not currently instantiated, superordinate role in hierarchy only.
- **Agent (participants of a project or activity)** - Actor	in	an event	who	initiates and carries out	the event intentionally or consciously,	and who exists independently of	the event. - *admit-65, beg-58.2, cooking-45.3, force-59*
- **Asset (changed assets, tools, systems, buildings, equipment affected by the activity)** - Value that is a concrete object. - *bill-54.5, pay-68*
- **Attribute** - Undergoer that is a property of an entity or entities, as opposed to the entity	itself. - *assessment-34.1, calabratable_cos 45.6*
- **Beneficiary (client, who used the result)** - Undergoer in a state or an event that is (potentially) advantaged or disadvantaged by the event or state. - *cost-54.2, get-13.5.1*
- **Cause (cause or justification for a change, project, activity)** - Actor in an event (that may be animate or inanimate) that initiates the event, but that	does not act with any intentionality or consciousness; it exists independently of the event. - *indicate-78, free-80*
- **Co-Agent** - Agent who is acting in coordination or reciprocally with another agent while participating in the same event (specific to events with symmetrical participants). - *cooperate-73, meet-36.3*
- **Co-Patient** - Patient that participates in an event with another patient, both participate equally in the event (specific to events with symmetrical participants). - *mix-22.1*
- **Co-Theme** - Theme that participates in an event or state with another Theme; both participate equally (thereby distinguishing this role from Pivot; specific to events with symmetrical participants). - *cling-22.5, multiply-108*
- **Destination (where did the end-user final products locate)** - Goal that is a concrete, physical location. - *bring-11.3, carry-11.4*
- **Duration** - Length or extent of time.
- **Experiencer** - Patient that is aware of the event undergone (specific to events of perception). - *flinch-40.5, see-30.1*
- **Extent (affected locations, places where job took place)** - Value indicating the amount of measurable change to a participant over the course of	the event. - *calabratable_cos-45.6*
- **Final_Time** - Time that indicates when an event ends or a state becomes false. - *Not currently	instantited, hierarchy only*
- **Frequency** - Number of occurrences of an event within a given time span. - *Not currently	instantited, hierarchy only*
- **Goal** - Place that is the end point of an action and exists independently of the event. - *adjust-26.9, convert-26.6.*
- **Initial_Location** - Source that indicates the concrete, physical location where an event begins or a state becomes true. - *bring-11.3, carry-11.4*
- **Instrument** - Undergoer in an event that is manipulated by an agent, and with which an intentional act is performed; it exists independently of the event. - *destroy-44, tape-22.4*
- **Location (where did your end-user reside)** - Place that is concrete. - *appear-48.1.1, coil-9.6*
- **Material (workplace, process, system used by the end-user)** - Patient that exists at the starting point of action (inheritance from Source), which is transformed through the event into a new entity; concrete or abstract. - *deduce-97.2, knead-26.5*
- **Participant** - Entity involved in a state or event.
- **Patient (end-user or operator whose work you changed with your results)** - Undergoer in an event that experiences a change of state, location or condition, that	is causally involved or directly affected by other participants, and exists independently of the event. - *break-45.1, poison-42.2*
- **Pivot (changes in the subject of work or contract)** - Theme that participates in an event with another theme unequally. Pivot is much more central to the event (thereby distinguishing it from Co-Theme). - *own-100, require-103*
- **Place** - Participant that represents the state in which an entity exists.
- **Product** - Result that is a concrete object. - *create-26.4, preparing-26.3*
- **Recipient (customer, who accepted the result)** - Destination	that	is	animate. - *bill-54.5*
- **Result** - Goal that comes into existence through the event. - *bend-45.2, break-45.1*
- **Source (where did the end-user inputs to the process locate)** - Place that is the starting point of action; exists independently of the event. - *substance_emission-43.4*
- **Stimulus** - Cause in an event that elicits an emotional or psychological response (specific to events of perception) - *sight-302., stimulus_subject-30.4*
- **Time** - Participant that indicates an instant or an interval of time during which a state exists or an event took place. - *continue-55.3*
- **Theme (subject of the contract, task or work order)** - Undergoer that is central to an event or state that does not have control over the way the event occurs, is not structurally changed by the event, and/or is characterized as being in a certain position or condition throughout the state. - *butter-9.9, hold-15.1*
- **Trajectory** - *escape-51.1, push-12*
- **Undergoer (acquirer, for whom was the job)** - Participant in a state or event that is not an instigator of the event or state.
- **Value** - Place along a formal scale. - *cost-54.2*