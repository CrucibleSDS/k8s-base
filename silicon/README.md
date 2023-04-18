# Silicon
This directory contains the Silicon manifests for Crucible.

## ConfigMap (`silicon-config-env`)
Additional config (strategic merge):
- `S3_URL` (s3 gateway base URL)
- `S3_BUCKET_NAME`
- `MEILI_URL` (Meilisearch internal URL)

## Secret (`silicon-secret-env`)
- `DATABASE_URL` (`postgresql+asyncpg://silicon:<postgres-password>@<postgres-host>:5432/silicon`)
- `MEILI_API_KEY` (Meili admin API key)
- `S3_ACCESS_KEY`
- `S3_SECRET_KEY`
