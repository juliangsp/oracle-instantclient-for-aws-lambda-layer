## Oracle DB Instant Client Light for AWS Lambda Layer using NodeJS 14.x / 16.x


Use Node package module: [oracledb / node-oracledb, currently latest version 5.5](https://www.npmjs.com/package/oracledb/v/5.5.0)

> Use node-oracledb 5.5.0 to connect Node.js 14, or later, to Oracle Database. Older versions of node-oracledb may work with older versions of Node.js.
> 
> Node-oracledb supports basic and advanced features of Oracle Database and Oracle Client. See the [homepage](https://oracle.github.io/node-oracledb/) for a list."

Per node-oracledb install documentation, [2. Quick Start node-oracledb Installation](https://oracle.github.io/node-oracledb/INSTALL.html#quickstart):

> * Add Oracle Client libraries version 21, 19, 18, 12, or 11.2 to your operating system library search path such as `PATH` on Windows or `LD_LIBRARY_PATH` on Linux. On macOS link the libraries to `/usr/local/lib`.
>   * If your database is remote, then get the libraries by downloading and unzipping the free [Oracle Instant Client](https://www.oracle.com/database/technologies/instant-client.html) “Basic” or “Basic Light” package for your operating system architecture.
>   * Instant Client on Windows requires an appropriate Visual Studio Redistributable. On Linux, the libaio (sometimes called libaio1) package is needed. When using Instant Client 19 on recent Linux versions, such as Oracle Linux 8, you may also need to install the libnsl package. This is not needed from Instant Client 21 onward.
>   * \[...\]

> Oracle Client libraries 21 can connect to Oracle Database 12.1 or greater. Oracle Client libraries 19, 18 and 12.2 can connect to Oracle Database 11.2 or greater. Version 12.1 client libraries can connect to Oracle Database 10.2 or greater. Version 11.2 client libraries can connect to Oracle Database 9.2 or greater.

Prepared library for [Oracle Instant Client Basic Light v18.5.0 for AWS Lambda Layer x86-64 for NodeJS runtime 14.x and 16.x](oracle-instantclient_18_5-lib.zip)

### Related Links:

[Oracle Instant Client Downloads for Linux x86-64 (64-bit)](https://www.oracle.com/database/technologies/instant-client/linux-x86-64-downloads.html)

Basic Light Package (ZIP) Version 18.5.0.0.0:
 
[instantclient-basiclite-linux.x64-18.5.0.0.0dbru.zip](https://download.oracle.com/otn_software/linux/instantclient/185000/instantclient-basiclite-linux.x64-18.5.0.0.0dbru.zip)


