## Dataset Summary 

The petal dataset is the product of a research project investigating flower physiology in _Eschscholzia californica_ at Mount Diablo State Park. Each row in the dataset corresponds to a petal collected from an indiviudal plant. This project is a work in progress, as I am currently in the process of collecting more data.

## Languages 

American English (en-US). 

## Data Fields 

**date:** string; the date the petal was collected and measured.

**week:** integer; the corresponding week in the fieldwork calendar.

**site:** string; the site designation from which the petal was collected. There are three Mount Diablo field sites: A, B, and C. Thus far, all data collection has commenced at site A.

**rep:** integer; the replicate within a given sampling week.

**plant:** string; an identification code used to specify an individual plant across different data files. 40 plants are sampled in a typical week, so in most cases a code designation is assigned between #1 - #40. Plants #1 - #20 represent the flower count sample, these code designations are fixed to the same individuals each week. Plants #21 - #40 represent the petal collection samples, these code designations are reassigned to a random sample of plants each week. The code designations match with the sample ID in the porometer dataset, and they will be used to append these data frames together at a future point. Less then 40 plants were sampled in weeks 1 through 3, therefore the code designations are irregular in these cases.

**p_freshMass:** integer; petal fresh mass in milligrams (mg). This is the mass of the flower petal collected from a given plant measured in the lab upon return from the field site. Petals were stored in plastic ziplock bags alongside a damp paper towel and transported in an icebox before measurement.

**p_surfaceArea:** integar; petal surface area in centimeters (cm). Petals were scanned in a photocopy machine and measured with ImageJ.

**p_dryMass:** integer; petal dry mass in milligrams (mg). Petals were dried in an oven at 70 degrees C for at least 48 hours.

**l_freshMass:** integer; leaf fresh mass in milligrams (mg). Leaves were only collected in week 4, hence why all other data fields contain the character 'n' for none. On a given individual plant, each leaf was proximal to the flower the petal was sourced from.

**l_surfaceArea:** integer; leaf surface area in centimeters (cm). Leaves were scanned in a photocopy machine and measured with ImageJ.

**l_dryMass:** integer; leaf dry mass in milligrams (mg). Leaves were dried in an oven at 70 degrees C for at least 48 hours.
