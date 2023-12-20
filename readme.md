## gsutil scripts

update TOCs

```bash
gsutil -m cp -r ./toc gs://arabic-phrasal-books.appspot.com/
```

update entire layer, all files

```bash
gsutil -m cp -r ./content/ar/arabiya-1 gs://arabic-phrasal-books.appspot.com/content/ar
```

update single file from a layer

```bash
gsutil -m cp -r ./content/ru/arabiya-1/015/007.txt gs://arabic-phrasal-books.appspot.com/content/ru/arabiya-1/015/007.txt
```

upload media files

```bash
gsutil -m cp -r ./content/media/arabiya-2 gs://arabic-phrasal-books.appspot.com/content/media
```
