# Getting-Started

## OS Information:
Command: hostnamectl</br>
Output: </br>
   Static hostname: hritikarajput-VirtualBox</br>
         Icon name: computer-vm</br>
           Chassis: vm</br>
        Machine ID: b0b3dcfd03064e38b753145dbee574d8</br>
           Boot ID: 0637a699dd2a41cd9832be7513b5fd10</br>
    Virtualization: oracle</br>
  Operating System: Ubuntu 16.04.6 LTS</br>
            Kernel: Linux 4.15.0-45-generic</br>
      Architecture: x86-64</br>

## Java Information
Command:java -version</br>
Output: </br>
	openjdk version "1.8.0_252" </br>
	OpenJDK Runtime Environment (build 1.8.0_252-8u252-b09-1~16.04-b09) </br>
	OpenJDK 64-Bit Server VM (build 25.252-b09, mixed mode) </br>

## Mysql Information
Command: status; </br>
Output: 

mysql  Ver 14.14 Distrib 5.7.30, for Linux (x86_64) using  EditLine wrapper</br>

Connection id:		22</br>
Current database:	users</br>
Current user:		root@localhost</br>
SSL:			Not in use</br>
Current pager:		stdout</br>
Using outfile:		'' </br>
Using delimiter:	; </br>
Server version:		5.7.30-0ubuntu0.16.04.1 (Ubuntu) </br>
Protocol version:	10</br>
Connection:		Localhost via UNIX socket</br>
Server characterset:	latin1</br>
Db     characterset:	latin1</br>
Client characterset:	utf8</br>
Conn.  characterset:	utf8</br>
UNIX socket:		/var/run/mysqld/mysqld.sock</br>
Uptime:			27 min 15 sec</br>

Threads: 1  Questions: 26  Slow queries: 0  Opens: 107  Flush tables: 1  Open tables: 26  Queries per second avg: 0.015</br>


Command: SHOW DATABASES; </br>
Output:

+--------------------+ </br>
| Database           | </br>
+--------------------+ </br>
| information_schema | </br>
| mysql              | </br>
| performance_schema | </br>
| sys                | </br>
| users              | </br>
+--------------------+ </br>
5 rows in set (0.00 sec) 

## Redis Information
Command: redis-cli </br>
127.0.0.1:6379>INFO </br>

Output: </br>

# Server
redis_version:5.0.8 </br>
redis_git_sha1:00000000</br>
redis_git_dirty:0</br>
redis_build_id:129cf1a0751f12a</br>
redis_mode:standalone</br>
os:Linux 4.15.0-45-generic x86_64</br>
arch_bits:64</br>
multiplexing_api:epoll</br>
atomicvar_api:atomic-builtin</br>
gcc_version:5.4.0</br>
process_id:7599</br>
run_id:5a12af56cf08d0eb6fa80fe78f373c31ea5e6bc3</br>
tcp_port:6379</br>
uptime_in_seconds:39</br>
uptime_in_days:0</br>
hz:10</br>
configured_hz:10</br>
lru_clock:14061947</br>
executable:/home/hritikarajput/Getting-Started/redis-server</br>
config_file:</br>

# Clients
connected_clients:1</br>
client_recent_max_input_buffer:2</br>
client_recent_max_output_buffer:0</br>
blocked_clients:0</br>

# Memory
used_memory:854200</br>
used_memory_human:834.18K</br>
used_memory_rss:5844992</br>
used_memory_rss_human:5.57M</br>
used_memory_peak:854200</br>
used_memory_peak_human:834.18K</br>
used_memory_peak_perc:100.12% </br>
used_memory_overhead:840998</br>
used_memory_startup:791304</br>
used_memory_dataset:13202</br>
used_memory_dataset_perc:20.99% </br>
allocator_allocated:1372992</br>
allocator_active:1617920</br>
allocator_resident:8343552</br>
total_system_memory:1033322496</br>
total_system_memory_human:985.45M</br>
used_memory_lua:37888</br>
used_memory_lua_human:37.00K</br>
used_memory_scripts:0</br>
used_memory_scripts_human:0B</br>
number_of_cached_scripts:0</br>
maxmemory:0</br>
maxmemory_human:0B</br>
maxmemory_policy:noeviction</br>
allocator_frag_ratio:1.18</br>
allocator_frag_bytes:244928</br>
allocator_rss_ratio:5.16</br>
allocator_rss_bytes:6725632</br>
rss_overhead_ratio:0.70</br>
rss_overhead_bytes:-2498560</br>
mem_fragmentation_ratio:7.20</br>
mem_fragmentation_bytes:5032792</br>
mem_not_counted_for_evict:0</br>
mem_replication_backlog:0</br>
mem_clients_slaves:0</br>
mem_clients_normal:49694</br>
mem_aof_buffer:0</br>
mem_allocator:jemalloc-5.1.0</br>
active_defrag_running:0</br>
lazyfree_pending_objects:0</br>

# Persistence
loading:0</br>
rdb_changes_since_last_save:0</br>
rdb_bgsave_in_progress:0</br>
rdb_last_save_time:1591120212</br>
rdb_last_bgsave_status:ok</br>
rdb_last_bgsave_time_sec:-1</br>
rdb_current_bgsave_time_sec:-1</br>
rdb_last_cow_size:0</br>
aof_enabled:0</br>
aof_rewrite_in_progress:0</br>
aof_rewrite_scheduled:0</br>
aof_last_rewrite_time_sec:-1</br>
aof_current_rewrite_time_sec:-1</br>
aof_last_bgrewrite_status:ok</br>
aof_last_write_status:ok</br>
aof_last_cow_size:0</br>

# Stats
total_connections_received:1</br>
total_commands_processed:1</br>
instantaneous_ops_per_sec:0</br>
total_net_input_bytes:31</br>
total_net_output_bytes:11468</br>
instantaneous_input_kbps:0.00</br>
instantaneous_output_kbps:0.00</br>
rejected_connections:0</br>
sync_full:0</br>
sync_partial_ok:0</br>
sync_partial_err:0</br>
expired_keys:0</br>
expired_stale_perc:0.00</br>
expired_time_cap_reached_count:0</br>
evicted_keys:0</br>
keyspace_hits:0</br>
keyspace_misses:0</br>
pubsub_channels:0</br>
pubsub_patterns:0</br>
latest_fork_usec:0</br>
migrate_cached_sockets:0</br>
slave_expires_tracked_keys:0</br>
active_defrag_hits:0</br>
active_defrag_misses:0</br>
active_defrag_key_hits:0</br>
active_defrag_key_misses:0</br>

# Replication
role:master</br>
connected_slaves:0</br>
master_replid:238df9da701cdb2bfb95212e60200059e07a3844</br>
master_replid2:0000000000000000000000000000000000000000</br>
master_repl_offset:0</br>
second_repl_offset:-1</br>
repl_backlog_active:0</br>
repl_backlog_size:1048576</br>
repl_backlog_first_byte_offset:0</br>
repl_backlog_histlen:0</br>

# CPU
used_cpu_sys:0.078277</br>
used_cpu_user:0.034684</br>
used_cpu_sys_children:0.000000</br>
used_cpu_user_children:0.000000</br>

# Cluster
cluster_enabled:0</br>

# Keyspace
127.0.0.1:6379
