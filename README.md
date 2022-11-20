# G Gauge
G Gauge is an Android App I created to help me keep track of my use of GFuel.  I've been currently 
using a few Google Keep Notes to keep track of things like the expiration dates of my Tubs/Sticks, 
the current capacity of my Tubs, the total amount of Energy formula, the total amount of 
Hydration formula I have on hand, what shaker I last used, and which shakers need to be cleaned 
after I used them.  I've also been using Google Calendar to keep track of when I had an Energy 
GFuel and when I had a Hydration GFuel.  I thought it would be nice to just have an app that did 
all that with just a few taps on the screen instead of me typing all that stuff out.

## The Idea
I want to use an SQLite database on the phone to store Shakers, Tubs, Sticks, and Events.  I'm 
hoping that will allow the User to add that stuff with just a few taps and then have the app 
track that stuff depending on what the User enters.

## Items for MVP
Here's a few things I want this app to have before a 1.0 Release:
- Add Shakers to track
  - Pick from a list of Shakers offered by companies like GFuel
  - Track date added
  - Track date last used
  - Track date last cleaned
- Add Tubs to track
  - Pick from a list of Tubs offered by companies like GFuel
  - Track date added
  - Track current capacity
  - Track expiration date
  - Track date last used
- Add Sticks to track
  - Pick from a list of single use Sticks offered by companies like GFuel
  - Track date added
  - Track expiration date
- Add Events a User can enter
  - Receive Item: add a Shaker, Tub, or Stick to collection
  - Drink Formula: used a Shaker and Tub/Stick today
  - Clean a Shaker
- A Calendar View (Activity)
  - See dates when Formula was used
  - Each Formula Type (Energy, Hydration, etc.) has a different color
  - See dates when Shakers were added
- Statics displayed on the Main Activity
  - Total Energy Formula Available
  - Average Rate of Energy Formula consumption: X/month over a year
  - A Gauge to graphically display Total Energy Formula / Average Annual Use
  - Total Hydration Formula Available
  - Average Rate of Energy Formula consumption: X/month over a year
  - A Gauge to graphically display Total Hydration Formula / Average Annual Use
- View Tubs/Sticks offered by companies
  - Grouped by Company
  - Search by Name of the flavor
  - Ability to Favorite a flavor
  - Favorite flavors shown at the top of this view

## Nice to add later
Here's some stuff to add later.  They won't currently help me, but I can see them being helpful 
down the line.
- Add offerings by competing companies (Advanced GG, Rogue Energy, Gamer Supps, etc.)
- Add Statics for Focus Formula
  - Total Focus Formula
  - Average Rate of consumption
  - A Gauge to graphically display Total Focus Formula / Average Annual Use
- Track Caffeine intake per day
  - FDA says the maximum Caffeine per day is 400mg
  - Add a way to add Caffeine to track that isn't Formula
  - Warn User when they are near the limit on the Main Activity
- Customization by the User
  - Change colors in the Calendar
  - Change Average Rate display: X/month, X/week, X/year, etc.
  - Change Amount of Caffeine per day allowed