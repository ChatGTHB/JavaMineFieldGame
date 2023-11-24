# JavaMineFieldGame

# Mine Field Game is Under Development...

# Loading...

Game Rules

- The game is text-based.
- It should be played over two-dimensional arrays and designed in MineSweeper class. 
- The user must specify the matrix size, i.e. the number of rows and columns. 
- A quarter of the number of elements of the array (elementNumber / 4) should be placed randomly. For example, if the array is 4x3 in size, the number of elements should be calculated with the formula (number of rows * number of columns) and the size should be 12. In this case the number of mines should be 12 / 4 = 3 (hint: you can create a second array to hold the positions of these mines). 
 - The user has to select a point on the matrix. Enter row and column values for point selection. 
 - Check if the selected point is within the boundaries of the array and if the condition is not met, request the point again. 
- If there is a mine at the point entered by the user, the game is lost. 
- If there are no mines, look at all locations touching the point (right, left, up, down, upper left diagonal, upper right diagonal, lower right diagonal, lower left diagonal) and write the sum of the number of mines around the point. If there are no mines touching the point, the value "0" should be assigned. 
- The user should win the game if he/she can select all the points without stepping on any mines. 

Oyun Kuralları:

- Oyun metin tabanlıdır.
- Çift boyutlu diziler üzerinden oynanmalı ve MineSweeper sınıfı içerisinde tasarlanmalı. 
- Matris boyutunu yani satır ve sütun sayısını kullanıcı belirlemeli. 
- Diziye ait eleman sayısının çeyreği (elemanSayisi / 4) kadar rastgele mayın yerleştirilmeli. Örneğin dizi 4x3 boyutunda - ise eleman sayısı (satırSayısı * sütunSayısı) formülü ile hesaplanmalı ve boyutu 12 olmalı. Bu durumda mayın sayısı 12 / 4 = 3 adet olmalıdır. (ipucu : bu mayınların konumlarını tutacak ikinci bir dizi oluşturabilirsiniz.) 
 - Kullanıcı matris üzerinden bir nokta seçmeli. Nokta seçimi için satır ve sütun değerlerini girmeli. 
 - Seçilen noktanın dizinin sınırları içerisinde olup olmadığını kontrol edilmeli ve koşul sağlanmazsa tekrar nokta istenmeli. 
- Kullanıcının girdiği noktada mayın var ise oyunu kaybetmeli. 
- Mayın yok ise, ilgili noktaya değen tüm konumlarına bakılmalı (sağı, solu, yukarısı, aşağısı, sol üst çapraz, sağ üst çapraz, sağ alt çapraz, sol alt çapraz) ve etrafındaki mayınların sayısının toplamı ilgili noktaya yazılmalı. Noktaya değen herhangi bir mayın yok ise "0" değeri atanmalı. 
- Kullanıcı hiç bir mayına basmadan tüm noktaları seçebilirse oyunu kazanmalı. 

