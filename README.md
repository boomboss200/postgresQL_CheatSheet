# postgresQL_CheatSheet
cheet sheet queries 

# get Properties for a table column as null or not 
SELECT 
    column_name, 
    is_nullable 
FROM 
    information_schema.columns 
WHERE 
    table_name = 'PerformanceThreshold' 
    AND column_name = 'ratingCycleReminder';
