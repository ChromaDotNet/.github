# ChromaDotNet

.NET libraries for [Chroma](https://www.trychroma.com/), the open-source vector database, and Chroma Cloud. Website: [chromadotnet.org](https://chromadotnet.org).

| Repository | Package | |
|---|---|---|
| [ChromaDB.Client](https://github.com/ChromaDotNet/ChromaDB.Client) | [![ChromaDotNet.Client](https://img.shields.io/nuget/v/ChromaDotNet.Client?label=ChromaDotNet.Client)](https://www.nuget.org/packages/ChromaDotNet.Client) [![ChromaDotNet.Client.DependencyInjection](https://img.shields.io/nuget/v/ChromaDotNet.Client.DependencyInjection?label=ChromaDotNet.Client.DependencyInjection)](https://www.nuget.org/packages/ChromaDotNet.Client.DependencyInjection) | The client for the Chroma v2 API and Chroma Cloud, tested with Chroma 0.4.10 to 1.5.9. It continues [ssone95/ChromaDB.Client](https://github.com/ssone95/ChromaDB.Client). |
| [CommunityToolkit/AI](https://github.com/CommunityToolkit/AI/tree/main/MEVD/src/Chroma) | [![CommunityToolkit.VectorData.Chroma](https://img.shields.io/nuget/v/CommunityToolkit.VectorData.Chroma?label=CommunityToolkit.VectorData.Chroma)](https://www.nuget.org/packages/CommunityToolkit.VectorData.Chroma) | The Chroma provider for Microsoft.Extensions.VectorData, in the AI Community Toolkit, built on ChromaDotNet.Client. Hybrid search on Chroma Cloud. |
| [ChromaDB.Testcontainers](https://github.com/ChromaDotNet/ChromaDB.Testcontainers) | [![ChromaDotNet.Testcontainers](https://img.shields.io/nuget/v/ChromaDotNet.Testcontainers?label=ChromaDotNet.Testcontainers)](https://www.nuget.org/packages/ChromaDotNet.Testcontainers) | A Testcontainers for .NET module: a throwaway Chroma container in your tests. |
| [ChromaDB.Aspire](https://github.com/ChromaDotNet/ChromaDB.Aspire) | [![ChromaDotNet.Aspire.Hosting](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Hosting?label=ChromaDotNet.Aspire.Hosting)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Hosting) [![ChromaDotNet.Aspire.Client](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Client?label=ChromaDotNet.Aspire.Client)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Client) | Aspire integrations: Chroma in the AppHost, and the client in your services. |

Samples:

- [ChromaDB.SemanticKernel.Sample](https://github.com/ChromaDotNet/ChromaDB.SemanticKernel.Sample): Semantic Kernel samples with Chroma as the vector store.
- [ChromaDB.AgentFramework.Sample](https://github.com/ChromaDotNet/ChromaDB.AgentFramework.Sample): Microsoft Agent Framework samples with Chroma as the vector store.

Upstream:

- **Accepted:** the VectorData provider, in the AI Community Toolkit ([CommunityToolkit/AI#58](https://github.com/CommunityToolkit/AI/pull/58)).
- **Approved, waiting to be merged:** the Aspire integrations, in the Aspire Community Toolkit ([CommunityToolkit/Aspire#2219](https://github.com/CommunityToolkit/Aspire/pull/2219)).
- **Proposed:** the Testcontainers module, in Testcontainers for .NET ([testcontainers/testcontainers-dotnet#1784](https://github.com/testcontainers/testcontainers-dotnet/pull/1784)).

This is a community project. It is not affiliated with or endorsed by Chroma.
