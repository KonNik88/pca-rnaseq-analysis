# PCA and UMAP analysis of RNA-seq datasets

Учебный проект по анализу bulk RNA-seq и scRNA-seq данных.

## Датасеты
- **Bulk RNA-seq**: HL-60 cell line, [GSE184891](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE184891)
- **scRNA-seq**: AML patient samples, [GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256)

## Цели проекта
- Провести QC анализ bulk RNA-seq на HL-60 с помощью PCA
- Проверить сходимость реплик
- Для scRNA-seq построить UMAP и кластеризацию
- Сделать выводы о различиях между группами

## Использованные методы
- PCA (sklearn)
- UMAP (scanpy)
- Визуализация (matplotlib, seaborn)

## Запуск
1. Установите зависимости:
   ```bash
   pip install -r requirements.txt
## Запустите ноутбук:
   ```bash
   jupyter notebook Practice_PCA_bulk_RNA_seq_scRNA_seq.ipynb

# PCA and UMAP analysis of RNA-seq datasets

PCA and UMAP analysis of bulk RNA-seq (HL-60, GSE184891) and scRNA-seq (AML, GSE116256) data.  
QC, visualization, clustering, and interpretation of results.

## 📘 Datasets
- **Bulk RNA-seq**: HL-60 cell line, [GSE184891](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE184891)
- **scRNA-seq**: AML patient samples, [GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256)

## 🔬 Project goals
- Perform QC analysis of bulk RNA-seq using PCA
- Assess replicates consistency
- Apply UMAP for scRNA-seq data and visualize clusters
- Draw conclusions about group differences

## 📊 Methods
- PCA (scikit-learn)
- UMAP (scanpy / umap-learn)
- Visualization (matplotlib, seaborn)

## 🚀 How to run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
## Launch the notebook:
   ```bash
   jupyter notebook Practice_PCA_bulk_RNA_seq_scRNA_seq.ipynb