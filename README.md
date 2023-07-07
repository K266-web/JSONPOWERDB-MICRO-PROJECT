                                          ""JAVASCRIPT OBJECT NOTAION POER DATABASE""

 "This project is all about basics of JsonPowerDB and DEVELOP forms and micro project "

 JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

*   Benefits of using JsonPowerDB

- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.

  
 *   Connection Token - Connecting to JPDB API.

Connection-token is used to interact with JsonPowerDB, it must be included in every request of jsonPowerDB for security purpose.


*     Response Headers in JPDB :

One or more of the following information may be returned in the response, all of which give time in milliseconds unit. All information will be returned with IML, IRL, IDL, ISL APIs.
serverTime - Time between receiving request and returning response by JsonPowerDB Server.
reqResTime - Time taken to convert request to reponse by the API (not in the KVP API). It's the combination of parseTime and execTime.
parseTime -Time taken to parse and validate the request.
execTime - Actual time of executing the validated request.


* JSON POWERDB IMPORTANT COMMANDS FOR P[ERFORMING OPERATIONS.

   @ INDEX  MANIPULATION LANGUAGES - PUT ,PUT-ALL, UPDATE , SET_ALL, SET , REMOVE.
   @  INDEX RETREIVAL LANGUAGES - GET , GET_BY_KEY ,GET_BY_RECORD ,GET_ALL, FIND , FIND_ALL.
   @   INDEX DEFINATION LANGUAGE -  ADD INDEX ,INDEX-COLUMN ,REMOVE_INDEX, REMOVE_RELATION ,REMOVE_DB.
  
