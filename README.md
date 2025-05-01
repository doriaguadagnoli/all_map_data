# Southern Literature Map Data
This repository stores all of the map data created for Eng 355 Southern Literature. The data was created through collaborative work across four novels:
- Their Eyes Were Watching God
- The Color Purple
- Salvage the Bones
- Shell Shaker

The data is organized by sub-directory in the `refined_data` folder. 

Each novel is listed by folder name (i.e. `color_purple`).

Within these folders there are four files that each contain a specific data set for each novel.
- `items_purchased_by_location.csv`
- `location_type_count.csv`
- `color_purple_purchased_from_location.csv`
- `color_purple_purchaser_location.csv`

### items_purchased_by_location

Lists what type of item was purchased at a specific geographic location. These are generic categories:
-good
-service
-land
-livestock
-money

### location_type_count

Table of all the locations and how often the activity there is:
-economic
-movement

### purchased_from_location
Demographic overview of race, class, and gender of who the seller is at a specific location


### purchaser_location
Demographic overview of race, class, and gender of who the buyer is at a specific location

# Mapbox Tileset Reference Table

Use the following Mapbox tileset IDs when importing layers into Mapbox Studio.

| CSV Filename                              | Mapbox Layer Name               | Mapbox ID                          |
|------------------------------------------|--------------------------------|------------------------------------|
| their_eyes_items_purchased_by_location.csv | their_eyes_items_layer          | `yourusername.their_eyes_items`     |
| their_eyes_location_type_count.csv        | their_eyes_location_count_layer | `yourusername.their_eyes_loc_count` |
| their_eyes_purchased_from_location.csv    | their_eyes_purchased_from_layer | `burgerjh.5qhs3wn4`    |
| their_eyes_purchaser_location.csv         | their_eyes_purchaser_location-5lu1q1      | `yourusername.their_eyes_purchaser` |
| color_purple_items_purchased_by_location.csv | color_purple_items_layer      | `yourusername.color_purple_items`   |
| color_purple_location_type_count.csv      | color_purple_location_count_layer | `yourusername.color_purple_loc_count` |
| color_purple_purchased_from_location.csv  | color_purple_purchased_from_layer | `yourusername.color_purple_seller`  |
| color_purple_purchaser_location.csv       | color_purple_purchaser_layer    | `yourusername.color_purple_purchaser` |
| salvage_bones_items_purchased_by_location.csv | salvage_bones_items_layer    | `yourusername.salvage_bones_items`  |
| salvage_bones_location_type_count.csv     | salvage_bones_location_count_layer | `yourusername.salvage_bones_loc_count` |
| salvage_bones_purchased_from_location.csv | salvage_bones_purchased_from_layer | `yourusername.salvage_bones_seller` |
| salvage_bones_purchaser_location.csv      | salvage_bones_purchaser_layer   | `yourusername.salvage_bones_purchaser` |
| shell_shaker_items_purchased_by_location.csv | shell_shaker_items_layer      | `yourusername.shell_shaker_items`   |
| shell_shaker_location_type_count.csv      | shell_shaker_location_count_layer | `yourusername.shell_shaker_loc_count` |
| shell_shaker_purchased_from_location.csv  | shell_shaker_purchased_from_layer | `yourusername.shell_shaker_seller`  |
| shell_shaker_purchaser_location.csv       | shell_shaker_purchaser_layer    | `yourusername.shell_shaker_purchaser` |

  
