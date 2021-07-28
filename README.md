# Mount Khantan Camera Trapping Data
This data are from my thesis in study of the habitat association of Sumatran Serow in the limestone outcrop in Mount Khantan which located in Sungai Siput, Perak, Malaysia.


### What is Serow?
If you never heard about this creature named serow i can tell you a bit about it.
Serow have body shape like goat but it is not a goat!
Serow belongs to family Bovidae which is a cow family. 
The resemble of serow and cow family is their number of mammary glands.

![Capricornis%20sumatraensis%20_45_.JPG](attachment:Capricornis%20sumatraensis%20_45_.JPG) 


While collecting data of the Serow there is also other animal captured in the camera trap a some are common species we see everyday and some are rare.

This data actually are from merging of 2 different table by the same column which is the camera trap which is:
 * the charactheristic of habitat around the located camera trap 
 * the species captured within the camera trap 

### This data are not perfect so to make it clean and neat:
The thesis study are focusing about the serow so the data for other species captured are not fully recorded

#### Remove unrelevant columns.
* deleting serow detection column because the data are bias. serow detection were collected from the whole **6171 camera trap sampling days** with **86 356 photo captures** while the other species where only for **80 camera trap days**

* deleting **animal_cameratrap.camera_trap** because it is similar with **camera_trap** because this csv are resulting from merging 2 table by the same column 

#### Rename columns.
with simple and understandable name

#### Remove the null value rows.
remove all the row with the unfinished business

#### Rename the `species` column with the following:
* PEAGON and PEAGONI : Columba domestica
* CROW : Corvus brachyrhynchos
* DOG : Canis lupus familiaris
* SQUIRREL : Ratufa bicolor
* LEOPARD CAT : Neofelis nebulosa 

### With the clean data frame, what i want to do is:

1. make a dictionary with each species common name so it will be easier to read the data.
2. calculate the relative abundance index.
>  the relative abundanced is the evenness distribution of individuals among species in a community. To calculate species relative abundance by : (Total Number of Individual species (Isi) / Total Number of Species Population) multiply by one hundred (100)
3. observe which habitat type have the most and the least species captured.

## THE END


```python

```
