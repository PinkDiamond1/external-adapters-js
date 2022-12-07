# DAR

![1.0.1](https://img.shields.io/github/package-json/v/smartcontractkit/external-adapters-js?filename=packages/sources/dar/package.json)

This document was generated automatically. Please see [README Generator](../../scripts#readme-generator) for more info.

## Environment Variables

| Required? |      Name       |           Description           |  Type  | Options |                              Default                              |
| :-------: | :-------------: | :-----------------------------: | :----: | :-----: | :---------------------------------------------------------------: |
|           |  API_ENDPOINT   | Base URL for DAR REST endpoints | string |         |          `https://api-beta.digitalassetresearch.com/v2`           |
|           | WS_API_ENDPOINT |     WS URL for the DAR API      | string |         | `wss://6xfpgjrsh4.execute-api.us-east-1.amazonaws.com/production` |
|    ✅     |   WS_API_KEY    |       Key for the DAR API       | string |         |                                                                   |
|    ✅     | WS_API_USERNAME |    Username for the DAR API     | string |         |                                                                   |

---

## Input Parameters

Every EA supports base input parameters from [this list](../../core/bootstrap#base-input-parameters)

| Required? |   Name   |     Description     |  Type  |         Options          | Default |
| :-------: | :------: | :-----------------: | :----: | :----------------------: | :-----: |
|           | endpoint | The endpoint to use | string | [price](#price-endpoint) | `price` |

## Price Endpoint

`price` is the only supported name for this endpoint.

### Input Params

| Required? | Name  |    Aliases     |                  Description                   |  Type  | Options | Default | Depends On | Not Valid With |
| :-------: | :---: | :------------: | :--------------------------------------------: | :----: | :-----: | :-----: | :--------: | :------------: |
|    ✅     | base  | `coin`, `from` | The symbol of symbols of the currency to query | string |         |         |            |                |
|    ✅     | quote | `market`, `to` |    The symbol of the currency to convert to    | string |         |         |            |                |

### Example

There are no examples for this endpoint.

---

MIT License