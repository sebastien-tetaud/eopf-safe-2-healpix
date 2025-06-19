# eopf-safe-2-healpix

### I. setup repo & env

1. Clone the repository:

```bash
git clone git@github.com:sebastien-tetaud/eopf-safe-2-healpix.git
cd eopf-safe-2-healpix
```

2. Create and activate a conda environment:

```bash
conda create -n ai_processor python==3.11.4
conda activate eopf
```
### II. setup cdse credentials

Set up your credentials by creating a `.env` file in the root directory with the following content:

```bash
touch .env
```
then:

```
ACCESS_KEY_ID=username
SECRET_ACCESS_KEY=password
```


