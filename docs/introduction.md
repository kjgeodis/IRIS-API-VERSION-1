# Introduction

Integrate with GEODIS using the IRIS API integration platform. The IRIS API is intended only for clients of GEODIS and access to the services offered through the API need to be approved and activated by GEODIS before they can be utilized.
The use of the IRIS API is not intended to drive data provisioning to other applications, reporting and/or BI purposes. GEODIS will not allow large bulk data extraction in a batched fashion and that type of use of the web service will be enforced by capping of the number of requests done per account or in severe cases by discontinuation of the user accounts involved in such usage patterns. 

> GEODIS reserves the right to enforce abuse and user of the web service that may be affecting performance of IRIS or surrounding sub systems.

For the full IRIS application, please access it via [IRIS Web Application](https://iris-demo.geodis.com/).

Included API operations:

- **TRACKING - List of shipments:** This request should be used to get a complete list of shipments for the defined period looking at the selected date type in the request.
- **TRACKING - Shipment details:** This script should be used to get detailed information about a specific shipment.
- **BOOKING - Create and update bookings:** All booking functions.
- **MILESTONES - Milestone request:** The main purpose for this script is for GEODIS agents to update milestones on shipments via the IRIS API instead of doing this manually via Milestone Entry in IRIS.

### A Note on this Personal Space

This initial Studio project template was cloned from the [Studio Templates](https://github.com/stoplightio/studio-templates) Github repository. If you find an error, or have an idea on how to improve this getting started template, please let us know in the issues section of that repository.

We plan to add additional sections on Prism (mocking), Spectral (linting), working with the filesystem, Git, and more in the future.

This template includes a couple of example APIs (Petstore and To-dos). You can create a new project, or open another folder on your computer, by clicking the `Project Selector` dropdown in the top left of the Studio UI.