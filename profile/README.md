# ChromaDotNet

.NET libraries for [Chroma](https://www.trychroma.com/), the open-source vector database, and Chroma Cloud.

| Repository | Package | |
|---|---|---|
| [ChromaDB.Client](https://github.com/ChromaDotNet/ChromaDB.Client) | [![ChromaDotNet.Client](https://img.shields.io/nuget/v/ChromaDotNet.Client?label=ChromaDotNet.Client)](https://www.nuget.org/packages/ChromaDotNet.Client) | The client: the Chroma v2 API, Chroma Cloud, tested with Chroma 0.4.10 to 1.5.9. It continues [ssone95/ChromaDB.Client](https://github.com/ssone95/ChromaDB.Client). |
| [ChromaDB.VectorData](https://github.com/ChromaDotNet/ChromaDB.VectorData) | [![ChromaDotNet.VectorData](https://img.shields.io/nuget/v/ChromaDotNet.VectorData?label=ChromaDotNet.VectorData)](https://www.nuget.org/packages/ChromaDotNet.VectorData) | A provider for Microsoft.Extensions.VectorData, with hybrid search on Chroma Cloud. |
| [ChromaDB.Testcontainers](https://github.com/ChromaDotNet/ChromaDB.Testcontainers) | [![ChromaDotNet.Testcontainers](https://img.shields.io/nuget/v/ChromaDotNet.Testcontainers?label=ChromaDotNet.Testcontainers)](https://www.nuget.org/packages/ChromaDotNet.Testcontainers) | A Testcontainers for .NET module: a throwaway Chroma container in your tests. |
| [ChromaDB.Aspire](https://github.com/ChromaDotNet/ChromaDB.Aspire) | [![ChromaDotNet.Aspire.Hosting](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Hosting?label=ChromaDotNet.Aspire.Hosting)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Hosting) [![ChromaDotNet.Aspire.Client](https://img.shields.io/nuget/v/ChromaDotNet.Aspire.Client?label=ChromaDotNet.Aspire.Client)](https://www.nuget.org/packages/ChromaDotNet.Aspire.Client) | Aspire integrations: Chroma in the app host, and the client in the services. |

Samples:

- [ChromaDB.SemanticKernel.Sample](https://github.com/ChromaDotNet/ChromaDB.SemanticKernel.Sample): Semantic Kernel samples with Chroma as the vector store.
- [ChromaDB.AgentFramework.Sample](https://github.com/ChromaDotNet/ChromaDB.AgentFramework.Sample): Microsoft Agent Framework samples with Chroma as the vector store.

The Testcontainers module and the Aspire integrations are also proposed upstream, in [testcontainers/testcontainers-dotnet#1784](https://github.com/testcontainers/testcontainers-dotnet/pull/1784) and [CommunityToolkit/Aspire#2219](https://github.com/CommunityToolkit/Aspire/pull/2219).

This is a community project. It is not affiliated with or endorsed by Chroma.
