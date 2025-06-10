# Adding Your Album Data

After creating your ```.csv``` file, you will need to place it where the application can access it. 
1. Rename your file to ```album-rankings.csv``` (if it is not already). 
2. Open the ```MyFavoriteAlbums-main``` folder that you unzipped earlier. 
3. Go into the ```data``` subfolder.
4. Replace the existing ```album-rankings.csv``` file with your version.

```
.
└── Downloads/
    └── MyFavoriteAlbums-main/
        ├── vinyl.R
        ├── number_one_albums.R
        ├── data/
            └── album-rankings.csv
        ├── compare_bands.R
        ├── app_ui.R
        ├── app_server.R
        ├── app.R
        ├── albums_by_year.R
        ├── albums_by_band.R
        └── README.md
```
Once your file is in place, the application will be able to find and load your album data when it runs.