# Araba kiralama sistemi

## Ödev 7
Entities, DataAccess, Business ve Console katmanlarını oluşturuldu.<br/>
Bir araba(Car) nesnesi oluşturuldu.<br/>
Özellik olarak : Id, BrandId, ColorId, ModelYear, DailyPrice, Description alanlarını eklendi.<br/>
InMemory formatta GetById, GetAll, Add, Update, Delete operasyonları yazıldı.<br/>
Consolda test edildi.

## Ödev 8
Car nesnesine ek olarak;Brand ve Color nesneleri eklendi.<br/>
Sql Server tarafında yeni bir veritabanı kuruldu. Cars,Brands,Colors tablolarını oluşturuldu.<br/>
Sisteme Generic IEntityRepository altyapısı yazıldı.<br/>
Car, Brand ve Color nesneleri için Entity Framework altyapısı yazıldı.<br/>
GetCarsByBrandId , GetCarsByColorId servisleri yazıldı.



