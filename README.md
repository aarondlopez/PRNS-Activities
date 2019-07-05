PRNS Activities 2013-2015

The dataset used for this analysis is the Parks, Recreation, and Neighborhood Services Department activities from 2013-2015 for the city of San Jose, California. I wanted to better understand the types of activities offered by the city and if citizens were participating in these activities. Government programs are an important part of our communities. They can offer opportunities to learn, grow, and be active with our neighbors and friends. In order for programs and activities to be successful its important that these services are utilized and in demand. By analyzing these activities government officials can make better decisions about how to allocate resources and time. This will lead to better community outcomes and a more responsible government.

Methods

    -Feature creation of age groups, revenues, years, and low attendance label
    -Age groups, revenues, and years were used for data exploration
    -The low attendance label feature was created for the classification model
    -An activity was determined to be “low attendance” if enrollment in the activity was 1 or less
    -Each activity was given a low attendance label of 1 (true) or 0 (false)
    -Low attendance labels also helped to determine proportion of activities with low enrollment
    -A Decision Tree Classifier model was used to predict activities with low attendance

