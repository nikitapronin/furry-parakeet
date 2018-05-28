# furry-parakeet
Just can't figure out how to perform my task, which is:
I need to attach the characteristics to the "bundle" column as follows: write in the header "id" of the characteristics, and write the values in the lines of the corresponding "bundle"
 here is the way I parsed the needed characteristics
bundle = features[1]
d2 = lapply(features$categories_google,jsonlite::fromJSON)
d4 = purrr::map(features$categories_google, jsonlite::fromJSON)
