### Run Instruction

RUN adalah instruksi untuk mengeksekusi perintah di dalam image <b>hanya pada saat build stage</b>.

#### Format

```
RUN command
```

```
RUN['executable', 'argument', '...']
```

#### Build

```
docker build -t lazlanrafar/run docker-file/2.run run --progress=plain --no-cache
```
