# gongyh/nf-core-scgs: Databases

If running the pipeline in a local environment, you can download the databases of various tools using `bin/setup.sh` script.
```bash
docker run -v /data:/data -w /data -u $(id -u):$(id -g) -it gongyh/scgs /bin/bash
(scgs_py36) root@a9cea5b5a003:/data# /opt/nf-core-scgs/bin/setup.sh
```

## Supported databases

The following databases are supported by gongyh/scgs pipeline:
  1) NCBI nt database
  2) Uniprot proteomes database
  3) Kraken database
  4) CheckM database
  5) EggNOG v5 database
  6) KOfam HMM database
  7) ResFinder database
  8) PointFinder database
  9) Funannotate database

