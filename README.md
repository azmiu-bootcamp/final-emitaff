## Bu məsələnin əsas mahiyyəti hər hansı X müəssisəsinin işçilərini və onların aldıqları maaşları təsvir etməkdir.
### Aşağdakı tələbləri ödəyən proqram qurun:

#### Program run olunarkən aşağdakı seçimlər çıxsın:

 - Ən çox maaş alan işçini tapmaq üçün **1**
 - Ən az maaş alan işçini tapmaq üçün **2**
 - Bütün işçilərin adları və onları adlarının qabağında onların aldıqları maaşı cədvəl şəklində göstərmək üçün **3**
  ədədi daxil edilsinş
  
  
**Bazanın strukturu aşağdakı kimidir:**
İşçi cədvəli (employee table)
<table>
  <tr>
    <th>No</th>
    <th>Name</th>
    <th>Surname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Aysel</td>
    <td>Həsənova</td>
    <td>23</td>
  </tr>
</table>

Maaş cədvəli(salary table)

<table>
  <tr>
    <th>No</th>
    <th>EmpNo</th>
    <th>Month</th>
    <th>Net</th>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
    <td>2</td>
    <td>540</td>
  </tr>
</table>

Burada nəzərə alın ki, hər bir işçi müxtəlif aylarda müxtəlif maaş ala bilər. Yəni, işçi cədvəli ilə maas cadvəli arasında 1-n (one to many) və ya 1-in çox-a əlaqəsi var.
