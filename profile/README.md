# ChromaDotNet

.NET libraries for [Chroma](https://www.trychroma.com/), the open-source vector database, and Chroma Cloud. Website: [chromadotnet.org](https://chromadotnet.org).

| Repository | Package | |
|---|---|---|
| [ChromaDB.Client](https://github.com/ChromaDotNet/ChromaDB.Client) | [![ChromaDotNet.Client](https://img.shields.io/nuget/v/ChromaDotNet.Client?label=ChromaDotNet.Client)](https://www.nuget.org/packages/ChromaDotNet.Client) [![ChromaDotNet.Client.DependencyInjection](https://img.shields.io/nuget/v/ChromaDotNet.Client.DependencyInjection?label=ChromaDotNet.Client.DependencyInjection)](https://www.nuget.org/packages/ChromaDotNet.Client.DependencyInjection) | The client for the Chroma v2 API and Chroma Cloud, tested with Chroma 0.4.10 to 1.5.9. It continues [ssone95/ChromaDB.Client](https://github.com/ssone95/ChromaDB.Client). |
| [CommunityToolkit/AI](https://github.com/CommunityToolkit/AI/tree/main/MEVD/src/Chroma) | [![CommunityToolkit.VectorData.Chroma](https://img.shields.io/nuget/v/CommunityToolkit.VectorData.Chroma?label=CommunityToolkit.VectorData.Chroma)](https://www.nuget.org/packages/CommunityToolkit.VectorData.Chroma) | The Chroma provider for Microsoft.Extensions.VectorData, in the AI Community Toolkit, built on ChromaDotNet.Client. Hybrid search on Chroma Cloud. |
| [ChromaDB.Testcontainers](https://github.com/ChromaDotNet/ChromaDB.Testcontainers) | [![ChromaDotNet.Testcontainers](https://img.shields.io/nuget/v/ChromaDotNet.Testcontainers?label=ChromaDotNet.Testcontainers)](https://www.nuget.org/packages/ChromaDotNet.Testcontainers) | A Testcontainers for .NET module: a throwaway Chroma container in your tests. |
| [ChromaDB.Local](https://github.com/ChromaDotNet/ChromaDB.Local) | [![ChromaDotNet.Local](https://img.shields.io/nuget/vpre/ChromaDotNet.Local?label=ChromaDotNet.Local)](https://www.nuget.org/packages/ChromaDotNet.Local) | Chroma on your machine, without Docker and without Python: the Chroma executable as a child process of your app. Preview. |
| [ChromaDB.Embeddings](https://github.com/ChromaDotNet/ChromaDB.Embeddings) | [![ChromaDotNet.Embeddings](https://img.shields.io/nuget/vpre/ChromaDotNet.Embeddings?label=ChromaDotNet.Embeddings)](https://www.nuget.org/packages/ChromaDotNet.Embeddings) | The default embedding function of Chroma: all-MiniLM-L6-v2, the same vectors as the Python client. Preview. |
| [ChromaDB.Aspire](https://github.com/ChromaDotNet/ChromaDB.Aspire) | [![ChromaDotNet.Aspire.Hosting](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Hosting?label=ChromaDotNet.Aspire.Hosting)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Hosting) [![ChromaDotNet.Aspire.Client](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Client?label=ChromaDotNet.Aspire.Client)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Client) | Aspire integrations: Chroma in the AppHost, and the client in your services. |

Samples:

- [ChromaDB.SemanticKernel.Sample](https://github.com/ChromaDotNet/ChromaDB.SemanticKernel.Sample): Semantic Kernel samples with Chroma as the vector store.
- [ChromaDB.AgentFramework.Sample](https://github.com/ChromaDotNet/ChromaDB.AgentFramework.Sample): Microsoft Agent Framework samples with Chroma as the vector store.

Used by:

- [CommunityToolkit.VectorData.Chroma](https://www.nuget.org/packages/CommunityToolkit.VectorData.Chroma): the Chroma provider for Microsoft.Extensions.VectorData, in the [AI Community Toolkit](https://github.com/CommunityToolkit/AI/blob/546aa1b8e306e7518b0225341ea62cd86c916297/MEVD/src/Chroma/Chroma.csproj#L18) of the .NET Foundation.
  - Used by:
    - [Generative AI for Beginners .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet/blob/359ffe5adf0cb74a397fd99af8786e14d0930ca3/samples/CoreSamples/RAGSimple-05MEAIVectorsChroma/RAGSimple-05MEAIVectorsChroma.csproj#L12): a RAG sample in the Microsoft course.
    - [LangChain .NET](https://github.com/tryAGI/LangChain/blob/4d8062616101cced1c6737aac7bc76535f6efc86/examples/LangChain.Samples.Chroma/LangChain.Samples.Chroma.csproj#L16): a RAG sample with Chroma.
    - [LangChain.Databases](https://github.com/tryAGI/LangChain.Databases/blob/17c118f863ef1437b4ecaa0222081eb045b38a87/src/IntegrationTests/LangChain.Databases.IntegrationTests.csproj#L19): the integration tests.
  - Cited in:
    - [Semantic Kernel](https://github.com/microsoft/semantic-kernel/blob/7e68276a4a85022dd4da255beae3263ab5cbf059/dotnet/src/VectorData/Chroma/README.md#L1): recommended for Chroma in .NET.
    - [LangChain.Databases](https://github.com/tryAGI/LangChain.Databases/blob/17c118f863ef1437b4ecaa0222081eb045b38a87/README.md#L36): recommended for Chroma in its README.
    - [Microsoft Agent Framework](https://github.com/microsoft/agent-framework/blob/deecbcb062198f926516f89b65e5b1676e4514c2/dotnet/samples/community-projects.md#L26): listed among the .NET community projects.
- CommunityToolkit.Aspire.Chroma: the Chroma client integration, in the [Aspire Community Toolkit](https://github.com/CommunityToolkit/Aspire/blob/523b84b27c5d019d242d95c2252046ba3619303c/src/CommunityToolkit.Aspire.Chroma/CommunityToolkit.Aspire.Chroma.csproj#L12) of the .NET Foundation.
- [BotSharp.Plugin.Chroma](https://github.com/SciSharp/BotSharp/blob/c8f632bf13bb22aed53c8ba63d41ee9e0e0fb75b/src/Plugins/BotSharp.Plugin.Chroma/BotSharp.Plugin.Chroma.csproj#L14): the Chroma vector database plugin of BotSharp, by SciSharp.
- [LlmTornado.VectorDatabases.ChromaDB](https://github.com/lofcz/LLMTornado/blob/d619b5d4c6558094cc2fcb663a5d6b55e6871233/src/LlmTornado.VectorDatabases.ChromaDB/LlmTornado.VectorDatabases.ChromaDB.csproj#L17): the Chroma connector of LLM Tornado.

On the way:

- [eShopLite](https://github.com/Azure-Samples/eShopLite/pull/72): the Azure sample's Chroma scenario moves to ChromaDotNet.Client, which fixes it on Chroma 1.x.
- [Testcontainers for .NET](https://github.com/testcontainers/testcontainers-dotnet/pull/1784): a Chroma module, tested with ChromaDotNet.Client.
- [Semantic Kernel samples](https://github.com/microsoft/semantic-kernel/pull/14602): Chroma in the multi-store vector search sample and in the VectorStoreRAG demo, through CommunityToolkit.VectorData.Chroma.
- [Semantic Kernel documentation](https://github.com/MicrosoftDocs/semantic-kernel-docs/pull/460): the C# page of the Chroma connector, through CommunityToolkit.VectorData.Chroma.
- [Chroma documentation](https://github.com/chroma-core/chroma/pull/7877): Semantic Kernel and Agent Framework pages for .NET, through CommunityToolkit.VectorData.Chroma.

This is a community project. It is not affiliated with or endorsed by Chroma.
