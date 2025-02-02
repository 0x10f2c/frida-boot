
<h1 align="center">
  <br>
  <br>
  frida-boot 👢
  <br>
</h1>

<h4 align="center">
  A binary instrumentation workshop, using <a href="https://frida.re" target="_blank">Frida</a>, for beginners!
  <p align="center">
    <a href="https://twitter.com/leonjza"><img src="https://img.shields.io/badge/twitter-%40leonjza-blue.svg" alt="@leonjza" height="18"></a>
    <a href="https://hub.docker.com/r/leonjza/frida-boot"><img alt="Docker Cloud Build Status" src="https://img.shields.io/docker/cloud/build/leonjza/frida-boot"></a>
  </p>
 </h4>

## quickstart

<img align="right" src="./images/frida-boot-web.png" height="320" alt="frida-boot">

- `git clone github.com/leonjza/frida-boot`
- `cd frida-boot`
- `./docker.sh pull`
- `./docker.sh run`

After running the container, all of the workshop content will be available at <http://localhost:9999>.

## slides

The latest slides for this workshop can be found on Google Slides [here](https://docs.google.com/presentation/d/1BK4CsGChSKI8BCVsg9Rlv0lY5AfsrbanhIRWnKaP0TI/edit?usp=sharing).

## manually building

The `Dockerfile` in this repository can be used to manually build the container. Feel free to edit it to suit your needs.

```bash
docker build -t frida-boot:local .
```
