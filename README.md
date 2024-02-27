Example Jakarta RESTful Web Services (JAX-RS) CICS application.

**Build**

**Deploy**

**Invoke**
URL
   - https://<host-name>:<port>/<context-root>/<REST-config>/<resource-config>
Method
   - GET
Path
   - <context-root> 
      - defined during deployment
   - <REST-config> 
      - "system"
   - <resource-config> 
      - "properties"   - will return the JVM properties of the target CICS Liberty JVM server
      - "stgprot"      - will return the Storage Protection configuration of the target CICS region
