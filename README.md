elifbeyzatok00: bu proje ve pdf için README hazırla

Workspace: Collecting workspace informationAşağıda projeniz ve PDF dosyanız için uygun bir README örneği bulabilirsiniz.

---

# Mini GPT

Bu proje, temel bir karakter düzeyinde dil modeli olan Mini GPT'nin PyTorch ile sıfırdan uygulanmasını içerir. Model, Shakespeare'in eserlerinden oluşan küçük bir veri kümesi üzerinde eğitilmiştir ve metin üretimi yapabilmektedir.

## İçerik

- **Mini_GPT.ipynb**: Mini GPT modelinin tüm kodunu ve eğitim sürecini içeren Jupyter defteri.
- **How_GPT_Is_Done.pdf**: GPT mimarisinin nasıl çalıştığını anlatan referans PDF dokümanı.

## Özellikler

- Transformer tabanlı karakter düzeyinde dil modeli
- Çok başlı kendine dikkat (Multi-Head Self Attention)
- Art arda bağlanmış Transformer blokları
- GPU desteği (CUDA)
- Metin üretimi için örnek fonksiyonlar

## Kullanım

1. Gerekli paketleri yükleyin:
    ```sh
    pip install torch tqdm
    ```

2. Mini_GPT.ipynb dosyasını Jupyter veya Google Colab'da açın.

3. Tüm hücreleri sırasıyla çalıştırın. Gerekirse veri otomatik olarak indirilecektir.

4. Eğitim tamamlandıktan sonra, modelden örnek metinler üretebilirsiniz.

## Modeli Geliştirmek İçin

- Model boyutunu (`n_embed`, `n_heads`, `n_layers`) artırabilirsiniz.
- Daha büyük bir veri kümesiyle eğitebilirsiniz.
- Öğrenme oranı ve eğitim adımlarını ayarlayabilirsiniz.
- LR scheduler ve weight decay gibi gelişmiş teknikler ekleyebilirsiniz.

## Kaynaklar

- [nanoGPT (Andrej Karpathy)](https://github.com/karpathy/nanoGPT)
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/en/index)
- How_GPT_Is_Done.pdf

---

**Not:** Daha fazla bilgi için How_GPT_Is_Done.pdf dosyasını inceleyebilirsiniz.