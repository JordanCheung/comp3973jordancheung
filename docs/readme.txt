"NW": "Data Source=max.bcit.ca;Database=Northwind;Persist Security Info=True;User ID=nw;Password="
services.AddDbContext<NorthwindContext>(options => options.UseSqlServer(Configuration.GetConnectionString("NW")));

portal.azure.com

git init
git add .
git status
git commit -m "1st commit"
