---
ID_PAGE: 25223
PG_TITLE: RawTexture
PG_VERSION: 2.1
TAGS:
    - BaseTexture
    - Texture
---
## Description

class [RawTexture](/classes/3.0/RawTexture) extends [Texture](/classes/3.0/Texture)



## Constructor

## new [RawTexture](/classes/3.0/RawTexture)(data, width, height, format, scene, generateMipMaps, invertY, samplingMode)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | format | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
## Members

### format : number



## Methods

### update(data) &rarr; void



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      

### static CreateLuminanceTexture(data, width, height, scene, generateMipMaps, invertY, samplingMode) &rarr; [RawTexture](/classes/3.0/RawTexture)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
### static CreateLuminanceAlphaTexture(data, width, height, scene, generateMipMaps, invertY, samplingMode) &rarr; [RawTexture](/classes/3.0/RawTexture)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
### static CreateAlphaTexture(data, width, height, scene, generateMipMaps, invertY, samplingMode) &rarr; [RawTexture](/classes/3.0/RawTexture)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
### static CreateRGBTexture(data, width, height, scene, generateMipMaps, invertY, samplingMode) &rarr; [RawTexture](/classes/3.0/RawTexture)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
### static CreateRGBATexture(data, width, height, scene, generateMipMaps, invertY, samplingMode) &rarr; [RawTexture](/classes/3.0/RawTexture)



#### Parameters
 | Name | Type | Description
---|---|---|---
 | data | ArrayBufferView |      
 | width | number |      
 | height | number |      
 | scene | [Scene](/classes/3.0/Scene) |      
optional | generateMipMaps | boolean |      
optional | invertY | boolean |      
