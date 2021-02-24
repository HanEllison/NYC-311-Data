# NYC-311-Data
SQL analysis of New York City 311 non-emergency data, 2016-2020.
Can the city improve the time it takes to close a 311 request ticket?

311 Database Notes: Transactional Tables
nyc_311_2016
nyc_311_2017
nyc_311_2018
nyc_311_2019
nyc_311_2020

Columns (present in all tables):
request_id, created_date, closed_date, status, communityboardid, address, cross_street, landmark, locationtype, facilitytype, addresstype, vehicletype, agency_code, responsibleagency, requesttype, category, request_details, source, latitude, longitude

311 Database Notes: Reference Table
nyc_311_reference

Columns:
communityboardid, borough, neighborhoods

