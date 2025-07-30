## Get started

This is a simple notebook for medgemma use if your GPU doesn't have enough VRAM to fit the whole model into it. Both system and video ram is used to run the model. 

## About MedGemma

MedGemma is a collection of [Gemma 3](https://ai.google.dev/gemma/docs/core)
variants that are trained for performance on medical text and image
comprehension. Developers can use MedGemma to accelerate building
healthcare-based AI applications. MedGemma comes in two variants: a 4B
multimodal version and a 27B text-only version.

MedGemma 4B utilizes a [SigLIP image encoder](https://arxiv.org/abs/2303.15343)
that has been specifically pre-trained on a variety of de-identified medical
data, including chest X-rays, dermatology images, ophthalmology images, and
histopathology slides. Its LLM component is trained on a diverse set of medical
data, including radiology images, histopathology patches, ophthalmology images,
dermatology images, and medical text.

MedGemma variants have been evaluated on a range of clinically relevant
benchmarks to illustrate their baseline performance. These include both open
benchmark datasets and curated datasets, with a focus on expert human
evaluations for tasks. Developers can fine tune MedGemma variants for improved
performance. Please read more about our work in our manuscript [link coming] and
consult our Intended Use Statement for more details.

## License

While the model is licensed under the
[Health AI Developer Foundations License](https://developers.google.com/health-ai-developer-foundations/terms),
everything in this repository is licensed under the Apache 2.0 license, see
[LICENSE](LICENSE).
