# Docker Images and Size Comparison
In this project, my aim is to a performance comparison from the perspective of CPU, Memory, and I/O. Also, compare each framework based on image size of container.

## Prerequisite
- `Java 8+`
- `Maven`
- `docker`
- `htop`

# Frameworks Image Size Comparison
<table>
    <tr>
        <th>Application</th>
        <th>Container Image Size</th>
    </tr>
    <tr>
        <td>Spring Boot</td>
        <td>80.7MB</td>
    </tr>
    <tr>
        <td>NodeJS</td>
        <td>113MB</td>
    </tr>
    <tr>
        <td>Quarkus</td>
        <td>132MB</td>
    </tr>
    <tr>
        <td>FastAPI (Alpine Python)</td>
        <td>54.9MB</td>
    </tr>
</table>

# Frameworks Performance Comparison
![performance comparison](https://github.com/AzarguNazari/Docker-images-comparison/blob/master/media/nodejs-spring-quarkus-comparison.png)
