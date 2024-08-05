# Rating System

Like Luogu, XMOJ-Script has a rating system. The rating system is used to determine the color of your username.

## How is Rating Calculated?
> Please note that this may change in the future.

Currently, your rating equals your AC rate, i.e.,
The number of accepted submissions divided by the total number of submissions. The rating is then multiplied by 1000
to get the final rating value.
Ratings are cached on the client side for one day.


## Rating Colors

The color of a username in XMOJ-Script is determined by the user's rating. The rating system assigns different colors based on the rating value:

> Please note that this may change in the future.
- **Red**: Assigned if the rating is greater than 500.
- **Yellow**: Assigned if the rating is between 400 and 500 (inclusive).
- **Green**: Assigned if the rating is between 300 and 400 (inclusive).
- **Blue**: Assigned if the rating is less than 300.

This system helps visually distinguish users based on their ratings.