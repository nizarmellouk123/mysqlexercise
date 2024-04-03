show variables like 'innodb_buffer_pool_size';

SELECT @@innodb_buffer_pool_size/1024/1024/1024;


show variables like 'innodb_log_file_size';
SELECT @@innodb_log_file_size/1024/1024/1024;

show variables like 'innodb_change_buffering';

show variables like 'innodb_io_capacity';

show variables like 'innodb_io_capacity_max';

show variables like 'innodb_stats_persistent';

show variables like 'innodb_thread_concurrency';

show variables like 'innodb_flush_log_at_trx_commit';

show variables like 'tmp_table_size';

show variables like 'max_heap_table_size';

show variables like 'foreign_key_checks';

show variables like 'UNIQUE_CHECKS';

show variables like 'optimizer_switch';

show var:wq!
iables like 'Innodb_read_io_threads';

show variables like 'Innodb_write_io_threads';

show variables like 'innodb_status_output_locks';

show variables like 'table_open_cache';

show variables like 'thread_cache_size';

--my.cnf
slow_query_log = 1
slow_query_log_file = /var/lib/mysql/MySQLServer1-slow.log
long_query_time = 2
log_output = file
innodb_buffer_pool_size = 820M
innodb_log_file_size = 600M
innodb_log_files_in_group = 2
innodb_change_buffering ='none'
innodb_io_capacity=200
innodb_io_capacity_max=1000
innodb_stats_persistent=ON
innodb_thread_concurrency = 0
innodb_flush_log_at_trx_commit = 1
tmp_table_size = 16M
max_heap_table_size = 16M
innodb_read_io_threads = 4
innodb_write_io_threads = 4
innodb_status_output_locks = 0
table_open_cache= 2000
thread_cache_size = 18
