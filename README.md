# Code

```
INSERT INTO public.data_2022 (id, country, explained_by_social_support) VALUES (3, 'sss', 2);

DELETE FROM data_2022;

ALTER TABLE data_2022 
ALTER COLUMN happiness_score TYPE TEXT,
ALTER COLUMN whisker_high TYPE TEXT,
ALTER COLUMN whisker_low TYPE TEXT,
ALTER COLUMN dystopia TYPE TEXT,
ALTER COLUMN explained_by_gdp_per_capita TYPE TEXT,
ALTER COLUMN explained_by_social_support TYPE TEXT,
ALTER COLUMN explained_by_healthy_life_expectancy TYPE TEXT,
ALTER COLUMN explained_by_freedom_to_make_life_choices TYPE TEXT,
ALTER COLUMN explained_by_generosity TYPE TEXT,
ALTER COLUMN explained_by_perceptions_of_corruption TYPE TEXT;
```

# psycopg2

```
pip3 install psycopg2
```


# Resources
1. https://www.pgadmin.org/
2. https://community.render.com/t/connecting-to-pgadmin/2024
