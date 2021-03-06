![npm](https://img.shields.io/npm/v/slim-select-prefabs)

# flatpickr-prefabs
A collection of slim-select prefabs

## Install
### NPM
`npm i slim-select-prefabs`
### CDN
`<script src="https://unpkg.com/slim-select-prefabs/dist/index.js"></script>`

## Usage
### Client
Add the class `ddlClientID` to your select element

**index.html**
```
<select id="ddlClientID" class="ddlClientID">
</select>
```
**index.js**
```
import { ddlClientInitialise } from 'slim-select-prefabs'

ddlClientInitialise()
```

### Client Contact
Add the class `ddlClientContactID` to your select element

**index.html**
```
<select id="ddlClientContactID" class="ddlClientContactID">
</select>
```
**index.js**
```
import { ddlClientContactInitialise } from 'slim-select-prefabs'

ddlClientContactInitialise()
```

### Log Contact Type
Add the class `ddlLogContactTypeID` to your select element

**index.html**
```
<select id="ddlLogContactTypeID" class="ddlLogContactTypeID">
</select>
```
**index.js**
```
import { ddlLogTypeInitialise } from 'slim-select-prefabs'

ddlLogTypeInitialise()
```

### Generic
Add the class `ddlGeneric` to your select element

**index.html**
```
<select id="ddlProducts" class="ddlGeneric">
</select>
```
**index.js**
```
import { ddlGenericInitialise } from 'slim-select-prefabs'

ddlGenericInitialise()
```
