# Rotary-Transformer
Enable Rotary Embedding for Neural Language Translation.
Original code copied from https://github.com/lucidrains/rotary-embedding-torch.git for rotary_embedding_torch.py and
Original code copied from https://github.com/hkproj/pytorch-transformer.git for rest of the file

I replaced classical positional embedding of original hkproj/pytorch-transformer (https://github.com/hkproj/pytorch-transformer.git) with rotary embedding of  lucidrains/rotary-embedding-torch (https://github.com/lucidrains/rotary-embedding-torch.git) and confirmed languge translation trainig improves significantly.

Original rotary embedding paper : https://arxiv.org/abs/2104.09864 

The main purpose I did this study is to apply rotary embedding in EDA design optimization project.
Circuit is very similar to language in terms of graph connection. Many of neat idea in NLP can be applied in mnay EDA circuit design application.
I really apreciate all the work done in NLP side so that other engineering domain can use this amazing infrastructure.
