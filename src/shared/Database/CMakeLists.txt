


SET(database_STAT_SRCS
   DBCFileLoader.cpp
   DBCFileLoader.h
   DBCStore.h
   Database.cpp
   Database.h
   DatabaseEnv.h   
   DatabaseImpl.h
   DatabaseMysql.cpp
   DatabasePostgre.cpp
   DatabaseMysql.h
   DatabasePostgre.h
   Field.cpp
   Field.h
   MySQLDelayThread.h
   PGSQLDelayThread.h
   QueryResult.h
   QueryResultMysql.cpp
   QueryResultMysql.h
   QueryResultPostgre.cpp
   QueryResultPostgre.h
   SQLStorage.cpp
   SQLStorage.h
   SqlDelayThread.cpp
   SqlDelayThread.h
   SqlOperations.cpp
   SqlOperations.h
)

add_library(database STATIC ${database_STAT_SRCS})
