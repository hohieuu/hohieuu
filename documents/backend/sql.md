SELECT 
    pid
    ,datname
    ,usename
    ,application_name
    ,client_hostname
    ,state
    ,client_port
    ,backend_start
    ,query_start
    ,query  
FROM pg_stat_activity

# RLS 

https://www.postgresql.org/docs/current/sql-createpolicy.html
