# Rüzgar Hızı Tahmin Modeli

Bu proje, belirli meteorolojik verileri kullanarak rüzgar hızını tahmin eden bir modeli içerir. Proje, Python programlama dili ve bazı popüler kütüphaneler kullanılarak geliştirilmiştir.

## Kullanım

Proje Python 3.x sürümleriyle uyumludur. Ana bağımlılıklar arasında pandas, matplotlib ve scikit-learn bulunmaktadır. Aşağıdaki adımları takip ederek projeyi kullanabilirsiniz:

1. Projeyi bilgisayarınıza klonlayın veya ZIP dosyası olarak indirin.
2. Gerekli Python kütüphanelerini yükleyin:
    ```bash
    pip install pandas matplotlib scikit-learn numpy
    ```
3. Veri setini 'wind_data.csv' adıyla projenin ana dizinine yerleştirin.
4. `train_and_predict` fonksiyonunu kullanarak rüzgar hızını tahmin edebilirsiniz. Fonksiyon, nem oranı, basınç ve sıcaklık değerlerini kullanarak gelecek bir günde rüzgar hızını tahmin eder.

Örnek kullanım:
```python
from your_module import train_and_predict

# Veri setini yükle
wind_data = pd.read_csv('wind_data.csv')

# Tahmin yap
train_and_predict(wind_data, [])
