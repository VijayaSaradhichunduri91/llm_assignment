# Netherlands IMF Report Analysis

This notebook analyses the Netherlands’ 2024 IMF Article IV report using Qwen, MiniLM embeddings and FAISS.

## Run in Google Colab

1. Open the notebook and select a T4 GPU.
2. Download the [IMF report](https://www.imf.org/-/media/files/publications/cr/2024/english/1nldea2024001.pdf).
3. Upload it as `netherlands_2024.pdf` through the Files sidebar.
4. Run all cells in order.

Internet access is needed for package and model downloads. No API key is required.

## Results

Outputs include summaries, indicators, thematic counts, RAG answers, evaluation results and a dashboard.

Files are saved in `outputs/` and packaged as `netherlands_results.zip`.

## Limitations

Some generated findings contain extraction or classification errors. Judge responses are not independent verification. Check results against the source PDF.

## License

Code: MIT License—see `LICENSE`. The IMF report and model weights retain their respective terms.

