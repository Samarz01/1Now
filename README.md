1Now Ops
A fleet support dashboard for car-rental operators. Support agents track incidents, work through a guided resolution flow against an SLA timer, and keep an eye on the fleet and key numbers.
Live demo

This is a front-end prototype. All vehicles, renters, tickets and metrics are sample data, and the SMS and operator buttons simulate sending.
Features
Dashboard
Stat cards for critical incidents, active cases, resolved today and fleet activity
Active incident list with filters for Lockout, Dispute and Access
Resolved-today list with time to close
New incident form that adds a ticket to the list
Guided lockout resolution
Five steps: Verify, Diagnose, Resolve, Notify, Close
SLA timer against a 15-minute target that turns amber, then red as time runs out
Cause picker (keys inside, app failure, key never received, dead fob) that recommends an action
Dispatch details with ETA and cost
Auto-drafted SMS to the renter and an alert for the operator
Close the case with compensation and severity, or escalate
Quick actions (locksmith, roadside, tow, credit, escalate, photos) and a live incident log
Fleet
Vehicle cards with status, monthly revenue and a utilization bar
Metrics
Revenue by vehicle class, incidents by type, direct vs marketplace bookings, SLA compliance
Built with
HTML5, CSS3 (custom properties, grid) and vanilla JavaScript in a single index.html. Fonts: Inter and IBM Plex Mono.
Run it
Download or clone the repo and open index.html in a browser. There is nothing to install.
git clone https://github.com/Samarz01/1Now.git
Roadmap
Responsive layout for phones and tablets
Back end and database so tickets persist
Login for support agents
Real SMS and notification integrations
Working vehicle and filter controls on the Fleet page
Author
Rao Samar | LinkedIn | raosamar97@gmail.com
