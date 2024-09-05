docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=Cloud2024" -p 1433:1433 --name sqlserver_container -d lafuentes203/mi_sql_server:tagname


download image: docker push lafuentes203/mi_sql_server:tagname
