# Western NC Hurricane Helene Landslides and Associated FEMA County Risk Ratings
This map depicts bivariate symbolization using point and county level data in the web mapping environment. It represents Western North Carolina (NC) landslide events and impact overlaid with county landslide risk ratings. Hurricane Helene caused widespread damage across Western NC in late September 2024. Record breaking rainfall amounts accompanied by a predecessor rainfall event caused catastrophic flash flooding and landslides impacting residents all over the region. This map was inspired by this [article](https://www.cbsnews.com/news/hurricane-helene-landslides-too-dangerous-to-rebuild/) showcasing a father and daughter directly impacted by a landslide event and additionally how landslides have impacted Western NC moving forward. This map is planned to be used as an aid in comparing landslide risk ratings and associated landslide events from Helene.

Choropleth symbolization and the chroma.js library are used to visualize and better understand landslide impact and occurrence with its associated county landslide risk rating. Placemarker visualization of each landslide location is depicted using the Font Awesome icon library and chroma.js library for categorical differences in landslide impact type. A custom Leaflet control is used to create the legend showing the choropleth sequential color palette and categorical landslide impacts. 



# Packages, Stylesheets, and Data
- **Leaflet.js**: map creation and customization
- **jQuery**: handling DOM manipulation and event handling
- **Leaflet.css and Google Fonts**: stylesheets for the design of the user interface
- **FontAwesome**: custom icons
- **Chroma.js**: color conversions and scales

**Data provided by:** (1) [United States Geological Survey](https://www.sciencebase.gov/catalog/item/674634a1d34e6d1dac3abddc) for landslides and their associated impact and (2) [Federal Emergency Management Agency](https://hazards.fema.gov/nri/data-resources) for county landslide risk ratings. 
