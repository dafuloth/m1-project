# Milestone 1 Project: Lilac Lounge

This project imagines a local music and events venue _Lilac Lounge_ who would like to have a new website in order to better promote the business and have more customers.

## Contents

- [Project goals](#project-goals)
  - [`Customer` goals](#customer-goals)
  - [`Patron` goals](#patron-goals)
  - [Business goals](#business-goals)
  - [User Stories](#user-stories)

## User Experience (UX)

### Project goals

This project aims to help the _Lilac Lounge_ promote their business by producing an eye-catching website that will improve their online presence.

The target audience will be:

- venue-booking `customers`: anyone looking to hire out a venue
- prospective `patrons`: audience members who may want to see a show at the venue

#### `Customer` goals

Customers may be musicians or other entertainers looking to hire a venue where their fans can come to see them perform. They may also be people who are looking to hire a function room for a private event like a birthday party.

Customer goals are:

- Evaluating if the venue will be suitable for their needs
- Information relating to the physical characteristics of the venue, e.g. size, capacity, location
- Can easily contact the venue to make bookings

Beginning on the home page, the customer can see the upcoming events at the _Lilac Lounge_ which can help to give them an idea of kind of _vibe_ they may find.

Right after the events calendar there is a call-to-action directed at customers: a link to the Contact form that the customer can click if their interest is piqued.

The website will help the customer to achieve these goals because:

- information about the venue is summarised on a dedicated _About Us_ page
- The Gallery will contain event photography showcasing the venue in action, which can serve to present the _Lilac Lounge_ as a well run popular venue
- the Contact form is easily accessed as a modal from any page of the website

#### `Patron` goals

Patrons are people who will visit the venue to see a show or attend an event.

Patron goals are:

- To find out what's on at the _Lilac Lounge_
- To have a good time

The website will reassure patrons that the _Lilac Lounge_ will allow them to achieve these goals because:

- the event calendar on the homepage will show them at a glance the upcoming events at the venue
- the gallery shows images of people having a good time and invite patrons to come along to have a good too

#### Business goals

The _business_ is the _Lilac Lounge_.

The goals of the business are:

- raise the profile of the _Lilac Lounge_ as a music and events venue
- attract more customers
- attract more patrons

The website can help to achieve these objectives because:

- when so much is accessible online, having a compelling online presence is essential to allow a business to be seen
- customers and patrons go hand in hand:
  - If the venue is seen to be able to draw a higher number of patrons, then that can attract more (and perhaps more prestigious) customers, who can be reassured that the venue is able to accommodate their events and/or provide them with an audience.
  - If the venue attracts big names and puts on more events, it will generate buzz and attract more patrons

#### User Stories

As a customer, I want to:

1. know what kind of events the venue has had experience hosting
2. learn about the physical characteristics of the venue:
    - size
    - capacity
    - location
3. easily contact the venue to discuss hiring the venue

As a patron, I want to:

1. know what's on at the _Lilac Lounge_
2. know how to get to the venue
3. be reassured that I'll have a good time

## Design

### The contact form

Initially the contact form was going to be on its own separate page. However, as I became more familiar with Bootstrap, I realised that it would be more effective to implement the contact form via a Bootstrap Modal in order to maintain focus on the content.

The benefit of using a modal for the contact form is that the user is not navigated away from the site content, and nor would they need to manually return to the originating page. Thus the user may be encouraged to continue exploring the website. Meanwhile, a separate contact form _page_ does not offer anything else besides a contact form which could prematurely signal the end of the user journey.

#### DRYing the contact form
It should be possible to access the contact form modal on any page of the website. In order to avoid duplicating the code of the contact form on every page, the HTML of the contact form is stored in the file `contact.html` and loaded dynamically using JavaScript wherever it is required.