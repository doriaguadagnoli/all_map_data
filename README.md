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
| aild_economic_count.csv | aild_economic_count-7ykpxd | `burgerjh.0yfcp5b6`     |burgerjh.ci8mwu3n|
| their_eyes_location_type_count.csv        | their_eyes_location_type_coun-dlgcuv | `burgerjh.4e3g2fm2` |
| their_eyes_items_purchased_by_location.csv | their_eyes_items_purchased_by-4jct68          | `burgerjh.0yfcp5b6`     |
| their_eyes_location_type_count.csv        | their_eyes_location_type_coun-dlgcuv | `burgerjh.4e3g2fm2` |
| their_eyes_purchased_from_location.csv    | their_eyes_purchased_from_loc-cjaye0 | `burgerjh.0dyfhlru`    |
| their_eyes_purchaser_location.csv         | their_eyes_purchaser_location-5lu1q1      | `burgerjh.5qhs3wn4` |
| color_purple_items_purchased_by_location.csv | color_purple_items_purchased_-bvhiq7      | `burgerjh.19zeh070`   |
| color_purple_location_type_count.csv      | color_purple_location_type_co-b8thji | `burgerjh.ajzgbuiz` |
| color_purple_purchased_from_location.csv  | color_purple_purchased_from_l-6q1wvs  | `burgerjh.awjw9ty8`  |
| color_purple_purchaser_location.csv       | color_purple_purchaser_locati-1r6303 | `burgerjh.b38x1pvx` |
| salvage_bones_items_purchased_by_location.csv | salvage_the_bones_items_purch-403qoi    | `burgerjh.d86s9bva`  |
| salvage_bones_location_type_count.csv     | salvage_the_bones_location_ty-2kcm4c | `burgerjh.5nprtd1s` |
| salvage_bones_purchased_from_location.csv | salvage_the_bones_purchased_f-653q5m | `burgerjh.3p4636ib` |
| salvage_bones_purchaser_location.csv      | salvage_the_bones_purchaser_l-9jqcjq   | `burgerjh.81rv5t56` |
| shell_shaker_items_purchased_by_location.csv | shell_shaker_items_layer      | `yourusername.shell_shaker_items`   |
| shell_shaker_location_type_count.csv      | shell_shaker_location_count_layer | `yourusername.shell_shaker_loc_count` |
| shell_shaker_purchased_from_location.csv  | shell_shaker_purchased_from_layer | `yourusername.shell_shaker_seller`  |
| shell_shaker_purchaser_location.csv       | shell_shaker_purchaser_layer    | `yourusername.shell_shaker_purchaser` |

  
