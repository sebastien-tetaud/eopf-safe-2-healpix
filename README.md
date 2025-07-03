# eopf-safe-2-healpix

### I. setup repo & env

1. Clone the repository:

```bash
git clone git@github.com:sebastien-tetaud/eopf-safe-2-healpix.git
cd eopf-safe-2-healpix
```

2. Create and activate a conda environment:

```bash
conda create -n eopf python==3.11.4
conda activate eopf
```
### II. setup CDSE credentials

- Create an account CDSE on https://dataspace.copernicus.eu/
- Get your API ACCESS_KEY_ID and SECRET_ACCESS_KEY token.

Set up your credentials by creating a `.env` file in the root directory with the following content:

```bash
touch .env
```
then:

```
ACCESS_KEY_ID=you_acces_key
SECRET_ACCESS_KEY=your_secret_key
```


