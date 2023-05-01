# latest image.
latest image is on dockerhub (0.33)
- https://hub.docker.com/repository/docker/inkimar/naturalist/tags?page=1&ordering=last_updated
- connection-url - ``` useSSL=false ```

```
<datasource jndi-name="java:/NaturDS" pool-name="NaturDS" use-ccm="true">
                    <connection-url>jdbc:mysql://nfdb:3306/taxonpages_v2?autoReconnect=true&amp;useSSL=false</connection-url>
                    <driver>mysql-connector-java-5.1.47.jar</driver>
                    <pool>
                        <min-pool-size>10</min-pool-size>
                        <max-pool-size>50</max-pool-size>
                        <prefill>false</prefill>
                        <flush-strategy>IdleConnections</flush-strategy>
                    </pool>
                    <security>
                        <user-name>mediaserver</user-name>
                        <password>mediaserver</password>
                    </security>
                    <validation>
                        <check-valid-connection-sql>SELECT 1</check-valid-connection-sql>
                        <background-validation>true</background-validation>
                        <background-validation-millis>60000</background-validation-millis>
                    </validation>
                </datasource>
```

# Source code for Naturforskaren
is located in a private repository here - https://github.com/Naturhistoriska/naturforskaren

## archive.org 

### naturalist_202305
- here is a working war - https://archive.org/details/naturalist_202305
- context set to '/'
- matomo-id



