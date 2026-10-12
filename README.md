# Introgreen AI Plant Finder

**Photo-based plant recommendations powered by AI, plant knowledge and Magento 2 product data.**

The Introgreen Plant Finder is an AI-assisted tool designed to help people choose suitable plants for their homes and indoor spaces.

Instead of searching through hundreds of products, users can upload a photo of their living room, bedroom, office or another location, select a specific spot and receive personalized plant recommendations.

**Try the Plant Finder:**


The Introgreen AI Plant Finder is available in five languages:

- 🇳🇱 **Dutch:** [Plantenkiezer](https://introgreen.nl/plantenkiezer)
- 🇩🇪 **German:** [Pflanzenfinder](https://introgreen.de/pflanzenfinder)
- 🇬🇧 **English:** [Plant Finder](https://introgreen.eu/plant-finder)
- 🇫🇷 **French:** [Sélecteur de plantes](https://fr.introgreen.eu/selecteur-de-plantes)
- 🇪🇸 **Spanish:** [Selector de plantas](https://es.introgreen.eu/selector-de-plantas)

The Plant Finder helps visitors discover suitable plants based on their environment, personal preferences and available products.

Photo-based recommendations are currently in beta.

**Status:** Active development – photo analysis in beta.

## Why we built it

Choosing the right houseplant involves more than appearance.

A plant that looks attractive in a photograph may not be suitable for the available daylight, space, temperature or care routine.

Traditional product filters can help, but users may not know which conditions matter or what kind of plant they need.

The Introgreen Plant Finder aims to bridge that gap by combining AI-assisted interaction with structured plant knowledge and real product information.

## How photo-based plant recommendations work

### 1. Upload a room photo

Users upload a photograph of the area where they want to place a plant.

The tool analyses visible features of the space, providing context for the recommendation process.

### 2. Select a location

The user selects the intended position within the photo, such as a table, windowsill or corner of the room.

This helps distinguish between different possible plant locations within the same space.

### 3. Clarify growing conditions

A photograph alone cannot reliably establish the amount of daylight a location receives throughout the day.

The Plant Finder can therefore ask additional questions about:

- Direct or indirect sunlight
- Available space and preferred plant dimensions
- Preferred maintenance level
- Pets in the household
- Other relevant growing conditions

User-provided information remains important when interpreting the image.

### 4. Match plants to the location

The Plant Finder uses plant requirements and structured product information to identify potentially suitable choices.

Relevant characteristics may include light requirements, maintenance needs, plant dimensions and environmental preferences.

### 5. Display available products

Recommendations are connected to Introgreen's Magento 2 product catalogue.

The resulting suggestions can include product information, dimensions, prices and availability, allowing visitors to explore actual plants rather than receiving only generic species recommendations.

## Example: choosing a plant for a living room

A visitor uploads a photograph of a living room and selects a location on a table.

The selected location might have limited space, a particular pot-size requirement or a window nearby.

The tool combines the photo with additional information provided by the visitor and searches for suitable plants in the catalogue.

The example demonstrates the complete process:

**Room photo → selected location → growing conditions → plant recommendations → product catalogue**

## Technical overview

The Plant Finder combines several components:

**AI-assisted image analysis**

Interprets visual context from uploaded room photographs while recognizing that important environmental conditions may not be measurable from an image alone.

**Structured plant knowledge**

Uses plant characteristics and care requirements to support more suitable recommendations.

**Context-aware interaction**

Collects additional information when the initial photo or question does not provide enough detail.

**Magento 2 integration**

Connects recommendations to the Introgreen catalogue, including relevant product characteristics and availability.

**Multilingual storefronts**

The Introgreen platform serves customers in Dutch, German, English, French and Spanish.

## Limitations and responsible recommendations

Photo analysis is a decision-support feature, not a substitute for measuring actual growing conditions.

For example:

- A bright-looking room does not necessarily receive sufficient daylight throughout the year.
- A window's appearance does not establish daily sun exposure.
- Temperature, humidity and watering habits cannot be reliably determined from a single photograph.
- Plant suitability may depend on information that is not visible.
- AI-generated interpretations and recommendations can be incorrect.

For these reasons, the Plant Finder incorporates additional user input and continues to undergo testing and refinement.

The photo-analysis functionality is currently in beta.

## Plant Finder and Plantcoach

Introgreen develops two related AI-assisted applications.

**Plant Finder** focuses on helping users select suitable plants for a location, including recommendations based on photographs and growing conditions.

**Plantcoach** focuses on plant-care questions, symptoms, troubleshooting and advice supported by Introgreen's plant knowledge.

Both projects reflect our aim to make reliable plant information easier to access.

Learn more:

- [Plantcoach documentation on GitHub](https://github.com/Introgreen/plantcoach)
- [Introgreen technology and company overview](https://github.com/Introgreen/introgreen)
- [Introgreen Plantcoach](https://introgreen.eu/plantcoach/)

## About Introgreen

[Introgreen](https://introgreen.nl) is a European online plant retailer offering houseplants, garden plants and related products.

Alongside its e-commerce activities, Introgreen develops plant information resources, recommendation tools and technical integrations to help customers choose and care for plants.

Our online presence includes Dutch, German, English, French and Spanish storefronts.

## Documentation repository

This public repository provides information about the Introgreen AI Plant Finder.

**It is not an open-source release of the application's source code.**

The underlying implementation, commercial integrations and private systems are not included.

## Nederlands

De Introgreen Plantenkiezer helpt bezoekers geschikte planten te vinden voor hun woonkamer, slaapkamer of kantoor.

Met de nieuwe fotofunctie kunnen bezoekers een foto uploaden, een specifieke plek aanwijzen en plantenadvies ontvangen op basis van de ruimte en aanvullende informatie.

De fotofunctie bevindt zich momenteel in de bètafase.

[Bekijk de Nederlandse Plantenkiezer](https://introgreen.nl/plantenkiezer).

---

Developed by [Introgreen](https://introgreen.eu).

*AI-assisted plant recommendations for real spaces and real plants.*
