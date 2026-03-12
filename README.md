## İçindekiler

* [01_Chapter (Hatırlatıcı Quizler)](#01_chapter-hatırlatıcı-quizler)
* [02_Chapter (Veri Bilimi Kütüphaneleri)](#02_chapter-veri-bilimi-kütüphaneleri)
* [03_Chapter (Advance Python)](#03_chapter-advance-python)
* [04_Chapter (Pytorch)](#04_chapter-pytorch)
* [requirements.txt](./requirements.txt)

## Bölüm İçerikleri

### 01_Chapter (Hatırlatıcı Quizler)
* [python_quiz_1.ipynb](./01_Chapter_beginning_quizzes/python_quiz_1.ipynb): Python girişine dair hatırlatıcı küçük quiz.
* [python_quiz_2.ipynb](./01_Chapter_beginning_quizzes/python_quiz_2.ipynb): Python girişine dair hatırlatıcı 2. küçük quiz.
* [python_quiz_3.ipynb](./01_Chapter_beginning_quizzes/python_quiz_3.ipynb): Python girişine dair hatırlatıcı 3. küçük quiz.

### 02_Chapter (Veri Bilimi Kütüphaneleri)
* [01_numpy_intro.ipynb](./02_Chapter_data_science_libraries/01_numpy_intro.ipynb): Numpy'a giriş yapıldı. **Array arithmetic**, **Indexing** ve `arange()` fonksiyonuna bakıldı.
* [02_numpy_intro.ipynb](./02_Chapter_data_science_libraries/02_numpy_matrices.ipynb): Matrix arithmetic konusuna bakıldı.
* [03_numpy_intro.ipynb](./02_Chapter_data_science_libraries/03_numpy_operations.ipynb): transpose()`, `reshape()` ve `shape` gibi fonksiyonlara bakıldı.
* [04_pandas_intro.ipynb](./02_Chapter_data_science_libraries/04_pandas_intro.ipynb): Series işlemleri yapıldı.
* [05_pandas_intro.ipynb](./02_Chapter_data_science_libraries/05_pandas_dataframe.ipynb): DataFrame'e giriş yapıldı.
* [06_pandas_data_frame_operations.ipynb](./02_Chapter_data_science_libraries/06_pandas_dataframe_operations.ipynb): **Missing Data** (boş veri) yönetimi ve **GroupBy** operasyonları incelendi.
* [07_pandas_df_concat_merge.ipynb](./02_Chapter_data_science_libraries/07_pandas_df_concat_merge.ipynb): Veri setlerini birleştirme (`merge`, `concat`) yöntemleri uygulandı.
* [08_pandas_df_apply.ipynb](./02_Chapter_data_science_libraries/08_pandas_df_apply.ipynb): **Custom Functions** ve **Lambda** ifadelerinin DataFrame üzerinde kullanımı (`apply()`) çalışıldı.
* [09_matplotlib_intro.ipynb](./02_Chapter_data_science_libraries/09_matplotlib_intro.ipynb): **Matplotlib** kütüphanesine giriş. **Eksen (Axes)** yönetimi ve **Subplot** (çoklu grafik) oluşturma mantığı incelendi. `figure()` objesi ile çizim yapıldı.
* [10_matplotlib_styles.ipynb](./02_Chapter_data_science_libraries/10_matplotlib_styles.ipynb): Grafik özelleştirme ve stiller. Veri dağılımını analiz etmek için **Scatter**, **Histogram** ve aykırı değer analizi için **Box Plot** (Kutu Grafiği) gibi farklı görselleştirme teknikleri uygulandı.
* [11_seaborn_intro.ipynb](./02_Chapter_data_science_libraries/11_seaborn_intro.ipynb): **Seaborn** ile istatistiksel veri görselleştirme. Veriyi farklı boyutlarda (multi-dimensional) analiz etmek için `hue`, `style`, `size` ve `col` gibi parametrelerin kullanımı çalışıldı. **Relational Plots** (`scatterplot`, `lineplot`) ve **Distribution Plots** (`displot`, `heatmap`) teknikleri uygulandı.
* [12_seaborn_boxplot.ipynb](./02_Chapter_data_science_libraries/12_seaborn_boxplot.ipynb): Kategorik verilerin dağılım analizi. **Box Plot** (Kutu Grafiği) ile çeyreklikler (quartiles), medyan ve aykırı değerlerin (outliers) görsel yorumlanması üzerine çalışıldı.
* [13_data_science_libraries_quiz_.ipynb](./02_Chapter_data_science_libraries/13_data_science_libraries_quiz.ipynb): 4 Kütüphane ile ilgili hatırlatıcı küçük örnekler yapıldı.

### 03_Chapter (Advance Python)
* [01_advance_python.ipynb](./03_Chapter_advance_python/01_Advance_python.ipynb): Python'da ileri seviye programlama ve **Nesne Yönelimli Programlama (OOP)** mimarisi üzerine çalışıldı.
    * **Metaprogramming:** Fonksiyon ve sınıfların davranışlarını değiştirmek için `decorator` ve `decorator combining` yapıları kullanıldı.
    * **Encapsulation & Data Management:** `property` decorator'lar (`getter`, `setter`, `deleter`) ile veri yönetimi sağlandı.
    * **Method Types:** Sınıf yapısını optimize etmek için `staticmethod`, `classmethod` ve `abstractmethod` (Soyutlama) farkları incelendi.
    * **Polymorphism & Inheritance:** `Method Overloading` ve `Overriding` prensipleri ile kalıtım yönetimi; `final` ve `typing` (Tip Belirleme) ile kod güvenliği sağlandı.

### 04_Chapter (Pytorch)
* [01_pytorch_intro.ipynb](./04_Chapter_pytorch/01_pytorch_intro.ipynb): PyTorch ekosistemine giriş yapıldı. Derin öğrenmenin temel yapı taşı olan Tensör (Tensor) yapısı ve vektörize işlemler incelendi:
    * **Tensör Öznitelikleri:** Tensörlerin bellekteki yerini belirleyen `device` (CPU/GPU), veri hassasiyetini belirleyen `dtype` ve gradyan takibi için kritik olan `requires_grad` parametreleri analiz edildi.
    * **Matematiksel Boyut Analizi:** Tensörlerin geometrik yapısını anlamak için shape (boyut bileşenleri) ve `dim()` kavramları üzerinde duruldu.
    * **Veri Tipleri:** Hesaplama hızını ve doğruluğunu etkileyen farklı tensör veri tiplerine(float32, int64 vb.) bakıldı.
* [02_pytorch_operations.ipynb](./04_Chapter_pytorch/02_pytorch_operations.ipynb): Tensör oluşturma yöntemleri ele alındı:
    * **Başlatma Metotları:** `zeros`, `ones` ve belirli bir aralığı kapsayan `arange` fonksiyonları kullanıldı. `ones_like` ile mevcut tensörlerin geometrik yapısını (shape) koruyarak yeni yapılar oluşturuldu. `random tensor` oluşturma teknikleri uygulandı.
* [03_pytorch_matrix_multiplication.ipynb](./04_Chapter_pytorch/03_pytorch_matrix_multiplication.ipynb): `torch.matmul()` ve `@` operatörü ile vektörize çarpı (dot product) işlemleri gerçekleştirildi.
* [04_pytorch_aggregation_manipulation.ipynb](./04_Chapter_pytorch/04_pytorch_aggregation_manipulation.ipynb): `max`,`min`,`argmax`,`argmin`,`median`,`mean`,`sum` gibi fonksiyonlara bakıldı. `reshaping` ve `view` ile tensör boyutları yeniden yapılandırıldı. `contiguous` ve `non-contiguous` terimleri açıklandı. `stacking` işlemleri ile tensör birleştirme senaryoları uygulandı. `squeeze` ve `unsqueeze`ile birim boyutların yönetimi (boyut ekleme/çıkarma) gerçekleştirildi. `permute` ile şekil indexi değiştirildi. `slicing` ve `indexing` işlemlerine bakıldı. `random_seed` işlevine bakıldı.
* [05_pytorch_device_settings.ipynb](./04_Chapter_pytorch/05_pytorch_device_settings.ipynb): CPU ile oluşturdugumuz tensorları nasıl GPU'ya dönüştürürüz ya da GPU ile oluşturulanı nasıl CPU'ya dönüştürürüz bu örnekler uygulandı. Tensorları manuel olarak nasıl GPU versiyona taşırız, context manager ve with keyboardu kullanarak nasıl taşırız ve default olarak GPU versiyonda oluşturmaya nasıl geçiş yaparız işlemlerine bakıldı.