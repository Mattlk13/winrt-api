---
-api-id: P:Windows.Security.Cryptography.Core.SymmetricAlgorithmNames.AesEcb
-api-type: winrt property
---

<!-- Property syntax
public string AesEcb { get; }
-->

# Windows.Security.Cryptography.Core.SymmetricAlgorithmNames.AesEcb

## -description
Retrieves a string that contains "AES_ECB".

## -property-value
String that contains "AES_ECB".

## -remarks
Use the string retrieved by this property to set the symmetric encryption algorithm name when you call the [OpenAlgorithm](symmetrickeyalgorithmprovider_openalgorithm_637226074.md) method on a [SymmetricKeyAlgorithmProvider](symmetrickeyalgorithmprovider.md) object. The string represents the Advanced Encryption Standard (AES) algorithm coupled with an electronic codebook (ECB) mode of operation.

## -examples

## -see-also
[SymmetricKeyAlgorithmProvider](symmetrickeyalgorithmprovider.md)