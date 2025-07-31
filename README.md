# TMDb - The Movie Database 

Là một nguồn thông tin điện ảnh phong phú và đa chiều, được trích xuất từ API chính thức của TMDb – một trong những nền tảng cơ sở dữ liệu phim lớn nhất thế giới. Dữ liệu bao gồm hàng chục ngàn bộ phim với các thuộc tính chi tiết như: tiêu đề, ngày phát hành, doanh thu, ngôn ngữ, điểm đánh giá, thể loại, từ khóa, thông tin diễn viên – đạo diễn, công ty sản xuất, quốc gia phát hành,...

---

## 📌 Nguồn Dữ Liệu

- [TMDb](https://www.themoviedb.org/)


## 📂 Cấu Trúc Thư Mục
```
TMDB/
│
├── Data/
│   ├── Processed/
│   │   ├── dim_collections.csv
│   │   ├── dim_genres.csv
│   │   ├── dim_keyword.csv
│   │   ├── dim_links.csv
│   │   ├── dim_person.csv
│   │   ├── dim_production_companies.csv
│   │   ├── dim_production_countries.csv
│   │   ├── dim_ratings.csv
│   │   ├── dim_role.csv
│   │   ├── dim_spoken_languages.csv
│   │   ├── fact_movie_credits.csv
│   │   ├── fact_movie_keywords.csv
│   │   └── fact_movies_metadata.csv
│   │
│   └── Raw/
│       ├── credits.csv
│       ├── keywords.csv
│       ├── links.csv
│       ├── links_small.csv
│       ├── movies_metadata.csv
│       ├── ratings.csv
│       ├── ratings_small.csv
│
├── Screenshot/
│ 
│
├── Scripts/
│   └── final_cleaning_data.ipynb
│
├── .gitattributes
└── README.md
```

