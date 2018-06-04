# MongoDB
This is an example of code for implementing MongoDB
C:\Users\brian>cd ..

C:\Users>cd ..

C:\>cd "\Program Files\MongoDB\Server\3.6\bin"

C:\Program Files\MongoDB\Server\3.6\bin>mongod
2018-06-03T14:25:16.507-0700 I CONTROL  [initandlisten] MongoDB starting : pid=20512 port=27017 dbpath=C:\data\db\ 64-bit host=DESKTOP-8KUA3D4
2018-06-03T14:25:16.507-0700 I CONTROL  [initandlisten] targetMinOS: Windows 7/Windows Server 2008 R2
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] db version v3.6.5
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] git version: a20ecd3e3a174162052ff99913bc2ca9a839d618
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] OpenSSL version: OpenSSL 1.0.2o-fips  27 Mar 2018
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] allocator: tcmalloc
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] modules: none
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] build environment:
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten]     distmod: 2008plus-ssl
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten]     distarch: x86_64
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten]     target_arch: x86_64
2018-06-03T14:25:16.508-0700 I CONTROL  [initandlisten] options: {}
2018-06-03T14:25:16.512-0700 I -        [initandlisten] Detected data files in C:\data\db\ created by the 'wiredTiger' storage engine, so setting the active storage engine to 'wiredTiger'.
2018-06-03T14:25:16.513-0700 I STORAGE  [initandlisten] wiredtiger_open config: create,cache_size=3046M,session_max=20000,eviction=(threads_min=4,threads_max=4),config_base=false,statistics=(fast),cache_cursors=false,log=(enabled=true,archive=true,path=journal,compressor=snappy),file_manager=(close_idle_time=100000),statistics_log=(wait=0),verbose=(recovery_progress),
2018-06-03T14:25:17.320-0700 I STORAGE  [initandlisten] WiredTiger message [1528061117:319959][20512:140708025229648], txn-recover: Main recovery loop: starting at 2/5760
2018-06-03T14:25:17.996-0700 I STORAGE  [initandlisten] WiredTiger message [1528061117:996604][20512:140708025229648], txn-recover: Recovering log 2 through 3
2018-06-03T14:25:18.585-0700 I STORAGE  [initandlisten] WiredTiger message [1528061118:585563][20512:140708025229648], txn-recover: Recovering log 3 through 3
2018-06-03T14:25:18.909-0700 I STORAGE  [initandlisten] WiredTiger message [1528061118:909076][20512:140708025229648], txn-recover: Set global recovery timestamp: 0
2018-06-03T14:25:19.255-0700 I CONTROL  [initandlisten]
2018-06-03T14:25:19.257-0700 I CONTROL  [initandlisten] ** WARNING: Access control is not enabled for the database.
2018-06-03T14:25:19.257-0700 I CONTROL  [initandlisten] **          Read and write access to data and configuration is unrestricted.
2018-06-03T14:25:19.261-0700 I CONTROL  [initandlisten]
2018-06-03T14:25:19.262-0700 I CONTROL  [initandlisten] ** WARNING: This server is bound to localhost.
2018-06-03T14:25:19.263-0700 I CONTROL  [initandlisten] **          Remote systems will be unable to connect to this server.
2018-06-03T14:25:19.264-0700 I CONTROL  [initandlisten] **          Start the server with --bind_ip <address> to specify which IP
2018-06-03T14:25:19.269-0700 I CONTROL  [initandlisten] **          addresses it should serve responses from, or with --bind_ip_all to
2018-06-03T14:25:19.270-0700 I CONTROL  [initandlisten] **          bind to all interfaces. If this behavior is desired, start the
2018-06-03T14:25:19.271-0700 I CONTROL  [initandlisten] **          server with --bind_ip 127.0.0.1 to disable this warning.
2018-06-03T14:25:19.272-0700 I CONTROL  [initandlisten]
2018-06-03T14:25:19.272-0700 I CONTROL  [initandlisten]
2018-06-03T14:25:19.273-0700 I CONTROL  [initandlisten] ** WARNING: The file system cache of this machine is configured to be greater than 40% of the total memory. This can lead to increased memory pressure and poor performance.
2018-06-03T14:25:19.274-0700 I CONTROL  [initandlisten] See http://dochub.mongodb.org/core/wt-windows-system-file-cache
2018-06-03T14:25:19.274-0700 I CONTROL  [initandlisten]
2018-06-03T14:25:19.588-0700 I FTDC     [initandlisten] Initializing full-time diagnostic data capture with directory 'C:/data/db/diagnostic.data'
2018-06-03T14:25:19.594-0700 I NETWORK  [initandlisten] waiting for connections on port 27017

Make To Do List directory & JSON file
C:\Users\brian>mkdir todoListApi

C:\Users\brian>cd todoListApi

C:\Users\brian\todoListApi>npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (todolistapi)
