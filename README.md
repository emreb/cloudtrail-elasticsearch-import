# cloudtrail-elasticsearch-import
Imports CloudTrail JSON into ElasticSearch


   * Install nodejs
   * run `npm install` in the root directory of the project
   * run `AWS_ACCESS_KEY=xxxxx AWS_SECRET_KEY=yyyyyy node import.sh.js <options>`
   * For better debugging, run `AWS_ACCESS_KEY=xxxxx AWS_SECRET_KEY=yyyyyy DEBUG=info,error,listS3Objs,ElasticSearch:error node import.sh.js <options>`
