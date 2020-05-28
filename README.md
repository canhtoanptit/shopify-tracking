# shopify-tracking

# run adm-socket
pm2 start index.js &

# build java file
mvn clean install -Pprod -DskipTests

# run jar
java -jar path-to-jar-file &
