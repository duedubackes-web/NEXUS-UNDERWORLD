# NEXUS UNDERWORLD — Rio Expansion (Design v0.1)

## Intent
Build an original, respectful, living open-world game region inspired by the geography and urban culture of Rio de Janeiro. Use licensed or independently created assets. Fictionalize criminal groups, leadership, operational details, and sensitive locations. Do not reproduce real individuals' private information or exact operational layouts.

## World districts (fictionalized)
- Costa Azul: beaches, tourism, beachfront roads, marinas
- Centro Antigo: transit hubs, markets, office blocks, heritage buildings
- Morro do Horizonte: steep hillside community, stairs, alleyways, local businesses, homes, schools, cultural centers
- Porto do Sol: port, warehouses, truck routes, shipping terminals
- Serra Verde: forested hills, winding roads, overlooks

## Society simulation
Residents have independent identities: names, languages, occupations, schedules, relationships, style, economic needs and personalities. Ethnicity or neighborhood never determines criminality or moral traits. Simulate community services, transit, events, street vendors, social ties, local music and sport.

## Fictional factions and story
- Civilian community groups and local leaders
- Fictional organized-crime factions with territory and reputation systems
- Fictional militia-like extortion organizations
- Police, investigative journalists, public defenders and municipal services
- Conflict systems track civilian safety, service disruptions, trust and long-term consequences.
Do not use real faction insignia, recruitment messaging, real operational methods or tactical layouts.

## Gameplay loops
1. Civilian delivery and transport jobs
2. Investigation and evidence-gathering missions
3. Rescue, evacuation and community assistance
4. Branching faction reputation and diplomacy
5. Vehicle ownership, repair, traffic and weather
6. Dynamic events, consequences and save-state persistence

## Unreal architecture (planned)
- World Partition for large districts and HLOD
- PCG for city blockouts, vegetation and prop distribution
- MassEntity/MassAI for crowds and traffic LOD
- Enhanced Input for traversal and driving
- Gameplay Tags, Data Assets and StateTree for AI
- Chaos Vehicles for wheeled transport
- Niagara and volumetric effects for weather
- Common save interfaces and deterministic world clock

## First playable slice
500m x 500m hillside-to-coast blockout, third-person movement, road access, pedestrian schedules, one drivable vehicle, basic weather and two nonviolent missions. Expand only after performance and usability validation.

## Quality gates
Test collision, traversal, navmesh, frame time, crowd density, streaming, mission state, accessibility, narrative review and provenance of every asset.

Status: design document only. No 3D Rio map, NPC AI, or faction simulation has yet been built or compiled.
