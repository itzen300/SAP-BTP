# SAP_BTP


Practical demonstration of SAP BTP certificate exam via task sets.
Document= https://cap.cloud.sap/docs/get-started/


project/
       db/
         schema.cds
         data/
            exam.logistics-shipments.csv
            exam.logistics-packages.csv
       srv/
          logistics-services.cds
          logistics-services.js
       package.json
       mta.yaml
       mta_archives/


code to check and verify are=
$ cf apps

code to check the error as a form of logs=
$ cf logs

# SAP BTP Practical Tasks

## Technologies
- SAP CAP
- Node.js
- CDS
- SAP BTP

## Tasks
- Logistics shipment management
- CAP services
- CSV data handling

## How to Run
npm install
cds watch
