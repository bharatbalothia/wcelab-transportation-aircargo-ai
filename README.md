# AI Enabled Air Cargo Supply Chain

AI enabled Supply Chain solution for Air Cargo business in transportation industry

## Systems In Vision

1. Shipper Mobile / Web App.  
*An AI enabled mobile and web application that allows shippers to*
    - Create, view, and update a booking placed directly with CARGO Airline
    - Track and trace an CARGO Airling booking
    - View invoices
    - Connect with CARGO Airline via chat or voice
1. Power Forwarder Platform.  
*A freight forwarder platform provided by CARGO Airline to enhance, simplify, and standardize forwarders' capability*
    1. Shipper Mobile / Web App.  
    *A simplified version of CARGO Airline Shipper Mobile / Web App reskined for forwarders*
    1. Power Forwarder Web App.  
    *An AI enabled web application that provides forwarders the capability to*
        - Create, view, update, and track bookings 
        - Aggregate shipper orders into booking quote to shop with CARGO Airline (other airlines in the future)
        - Track and trace aggregated CARGO Airline bookings
    1. Forwarder Operation Mobile App.  
    *A mobile focused app that provides opertional process and tracking*
        - Receive packages from shipper
        - Track packages in stagging area
        - Record package delivery to CARGO Airline
1. CARGO Airline Opertaion Assistant.  
*An AI operation module to assist CARGO Airline agents in*
    - Create, view, and update bookings
    - Query and view cargo availability
    - Track and trace cargo shipments (AWB)
    - Proactively monitor and respond to cargo fulfillment interruption

## Epics

### Epic 1 Lightning Reflex

IBM enables CARGO airline to proactively address concerns due to flight interruption. 

https://youtu.be/qFWEMr6xOpU

#### Actors
- Li | Shipper for a Pharmacutical company
- Al | Shipper for a eletrioncial company
- Ray | Associate of Acme Freight Forwarder
- Liz | Associate of CARGO Airline

#### Plot
1. Li uses ACME app to ship a package of medicine
    1. Li uses IBM team's technology to input the package dimension by taking a picture
    1. The picture is part of the shipment data
1. Al uses ACME website to ship a package of eletronic
1. Ray uses a CARGO Airline's Power Forwarder to consolidate Li and Al's orders into a freight forward order
1. ACME Freight Forwarder uses CARGO Airline's Power Forwarder application to receive packages from Li and Al
1. ACME Freight Forwarder brings Li and Al's packages to CARGO Airline airport location
1. CARGO Airline loads Li and Al's packages to a ULD for a flight
1. the flight is delay due to weather
1. Liz receives notificaiton about flight delay
1. Liz utilizes SCI to overview the shipment statuses
    1. Liz uses dashboard to get an overview of the statuses
    1. Liz drill down into a client's shipment
    1. Liz wants to provide customer a better alternatie
    1. Liz works with AI to list the options
    1. Liz, AI, and Ray conference about the resultion
    1. SCI AI executes the agreed resultion

  
### Epic 2 Power Forwarder

IBM helps CARGO airline connecting with its freight forwarder customers and simplifing the tracking and quoting process.

Draft video: https://youtu.be/D_tlxq97jc4

#### Actors

- Ray | Associate of Acme Freight Forwarder 
- Liz | Associate of CARGO Airline

#### Plot
1. Ray opens CARGO airline's Power Forwarder portal and is welcomed with a dashboard of order status and important messages
1. Ray sees a list of shipments in process and checked on few that were rerouted
1. Ray is happy that all her customers' shipments' status and locations
1. Ray has a list of packages to be shipped.
   1. The list is in a spreadsheet
   1. Each entry has the type (Pharma, Horse...), service level, ship date, from, to, dimensions, weight, ...
1. Ray wants to check on the availability and pricing for the list 
1. Ray uploads the list
1. Ray receives the suggested break down of AWB and pricing matrix for each AWB by ship date and arriving date
1. Ray removed an item from an AWB to see if she can get better pricing
1. Ray thinks there might be a better way to pricing this AWB since it has an odd shap but she believe it would still fit in an ULD
1. Ray save the quote and click on "Chat" to chat with a CARGO airline associate about this quote
1. Liz received the chat request with the Quote number
1. Liz opens the quote in her call center application
1. Ray and Liz chat...
1. Liz upated the quote to reflect what Liz described
1. Ray sees the updated quote and is happy
1. Ray converts the quotes to orders
