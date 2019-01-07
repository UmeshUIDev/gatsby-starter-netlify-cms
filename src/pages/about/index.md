---
templateKey: about-page
title: About our values
---
### export enum ProductType {

###   Activity = 'ACTIVITY',

###   Hotel = 'HOTEL',

###   Flight = 'FLIGHT',

###   Ferry = 'FERRY',

### }

### 

### export enum StatusName {

###   Quote = 'quote',

###   Paid = 'paid',

###   Cancelled = 'cancelled',

###   Travelled = 'travelled',

###   Confirmed = 'confirmed unpaid',

###   Unavailable = 'unavailable',

### }

### 

### export enum PaxType {

###   Adult = 'ADT',

###   Child = 'CNN',

###   Infant = 'INF',

### }

### 

### export const  currencyList = \[{"key": "AUD",value:"AUD"},{key:"EUR",value:"EUR"},{key:"GBP",value:"GBP"},{key:"USD",value:"USD"},{key:"AFN",value:"AFN"},{key:"ALL",value:"ALL"},{key:"DZD",value:"DZD"},{key:"AOA",value:"AOA"},{key:"ARS",value:"ARS"},{key:"AMD",value:"AMD"},{key:"AWG",value:"AWG"},{key:"AZN",value:"AZN"},{key:"BSD",value:"BSD"},{key:"BHD",value:"BHD"},{key:"BDT",value:"BDT"},{key:"BBD",value:"BBD"},{key:"BYR",value:"BYR"},{key:"BZD",value:"BZD"},{key:"BMD",value:"BMD"},{key:"BTN",value:"BTN"},{key:"BOB",value:"BOB"},{key:"BAM",value:"BAM"},{key:"BWP",value:"BWP"},{key:"BRL",value:"BRL"},{key:"BND",value:"BND"},{key:"BGN",value:"BGN"},{key:"BIF",value:"BIF"},{key:"KHR",value:"KHR"},{key:"CAD",value:"CAD"},{key:"CVE",value:"CVE"},{key:"KYD",value:"KYD"},{key:"CLP",value:"CLP"},{key:"CNY",value:"CNY"},{key:"COP",value:"COP"},{key:"XOF",value:"XOF"},{key:"XAF",value:"XAF"},{key:"KMF",value:"KMF"},{key:"XPF",value:"XPF"},{key:"CDF",value:"CDF"},{key:"CRC",value:"CRC"},{key:"HRK",value:"HRK"},{key:"CUC",value:"CUC"},{key:"CUP",value:"CUP"},{key:"CZK",value: "CZK"},{key:'DKK',value:'DKK'},{key:'DJF',value:'DJF'},{key:'DOP',value:'DOP'},{key:'XCD',value:'XCD'},{key:'EGP',value:'EGP'},{key:'SVC',value:'SVC'},{key:'ERN',value:'ERN'},{key:'CNH',value:'CNH'},{key:'BYN',value:'BYN'},{key:'ZMW',value:'ZMW'},{key:'EEK',value:'EEK'},{key:'ETB',value:'ETB'},{key:'FKP',value:'FKP'},{key:'FJD',value:'FJD'},{key:'GMD',value:'GMD'},{key:'GEL',value:'GEL'},{key:'GHS',value:'GHS'},{key:'GIP',value:'GIP'},{key:'XAU',value:'XAU'},{key:'GTQ',value:'GTQ'},{key:'GGP',value:'GGP'},{key:'GNF',value:'GNF'},{key:'GYD',value:'GYD'},{key:'HTG',value:'HTG'},{key:'HNL',value:'HNL'},{key:'HKD',value:'HKD'},{key:'HUF',value:'HUF'},{key:'ISK',value:'ISK'},{key:'INR',value:'INR'},{key:'IDR',value:'IDR'},{key:'XDR',value:'XDR'},{key:'IRR',value:'IRR'},{key:'IQD',value:'IQD'},{key:'IMP',value:'IMP'},{key:'ILS',value:'ILS'},{key:'JMD',value:'JMD'},{key:'JPY',value:'JPY'},{key:'JEP',value:'JEP'},{key:'JOD',value:'JOD'},{key:'KZT',value:'KZT'},{key:'KES',value:'KES'},{key:'KWD',value:'KWD'},{key:'KGS',value:'KGS'},{key:'LAK',value:'LAK'},{key:'LVL',value:'LVL'},{key:'LBP',value:'LBP'},{key:'LSL', value: 'LSL'}, {key: 'LRD', value: 'LRD'}, {key: 'LYD', value: 'LYD'}, {key: 'LTL', value: 'LTL'}, {key: 'MOP', value: 'MOP'}, {key: 'MKD', value: 'MKD'}, {key: 'MGA', value: 'MGA'}, {key: 'MWK', value: 'MWK'}, {key: 'MYR', value: 'MYR'}, {key: 'MVR', value: 'MVR'}, {key: 'MRU', value: 'MRU'}, {key: 'MRO', value: 'MRO'}, {key: 'MUR', value: 'MUR'}, {key: 'MXN', value: 'MXN'}, {key: 'MDL', value: 'MDL'}, {key: 'MNT', value: 'MNT'}, {key: 'MAD', value: 'MAD'}, {key: 'MZN', value: 'MZN'}, {key: 'MMK', value: 'MMK'}, {key: 'NAD', value: 'NAD'}, {key: 'NPR', value: 'NPR'}, {key: 'ANG', value: 'ANG'}, {key: 'NZD', value: 'NZD'}, {key: 'NIO', value: 'NIO'}, {key: 'NGN', value: 'NGN'}, {key: 'KPW', value: 'KPW'}, {key: 'NOK', value: 'NOK'}, {key: 'OMR', value: 'OMR'}, {key: 'PKR', value: 'PKR'}, {key: 'XPD', value: 'XPD'}, {key: 'PAB', value: 'PAB'}, {key: 'PGK', value: 'PGK'}, {key: 'PYG', value: 'PYG'}, {key: 'PEN', value: 'PEN'}, {key: 'PHP', value: 'PHP'}, {key: 'XPT', value: 'XPT'}, {key: 'PLN', value: 'PLN'}, {key: 'QAR', value: 'QAR'}, {key: 'RON', value: 'RON'}, {key: 'RUB', value: 'RUB'}, {key: 'RWF', value: 'RWF'}, {key: 'SHP', value: 'SHP'}, {key: 'WST', value: 'WST'}, {key: 'STD', value: 'STD'}, {key: 'STN', value: 'STN'}, {key: 'SAR', value: 'SAR'}, {key: 'SPL', value: 'SPL'}, {key: 'RSD', value: 'RSD'}, {key: 'SCR', value: 'SCR'}, {key: 'SLL', value: 'SLL'}, {key: 'XAG', value: 'XAG'}, {key: 'SGD', value: 'SGD'}, {key: 'SKK', value: 'SKK'}, {key: 'SBD', value: 'SBD'}, {key: 'SOS', value: 'SOS'}, {key: 'ZAR', value: 'ZAR'}, {key: 'KRW', value: 'KRW'}, {key: 'LKR', value: 'LKR'}, {key: 'SDG', value: 'SDG'}, {key: 'SRD', value: 'SRD'}, {key: 'SZL', value: 'SZL'}, {key: 'SEK', value: 'SEK'}, {key: 'CHF', value: 'CHF'}, {key: 'SYP', value: 'SYP'}, {key: 'TWD', value: 'TWD'}, {key: 'TJS', value: 'TJS'}, {key: 'TZS', value: 'TZS'}, {key: 'THB', value: 'THB'}, {key: 'TOP', value: 'TOP'}, {key: 'TTD', value: 'TTD'}, {key: 'TND', value: 'TND'}, {key: 'TRY', value: 'TRY'}, {key: 'TMM', value: 'TMM'}, {key: 'TMT', value: 'TMT'}, {key: 'TVD', value: 'TVD'}, {key: 'UGX', value: 'UGX'}, {key: 'UAH', value: 'UAH'}, {key: 'AED', value: 'AED'}, {key: 'UYU', value: 'UYU'}, {key: 'UZS', value: 'UZS'}, {key: 'VUV', value: 'VUV'}, {key: 'VEB', value: 'VEB'}, {key: 'VES', value: 'VES'}, {key: 'VEF', value: 'VEF'}, {key: 'VND', value: 'VND'}, {key: 'YER', value: 'YER'}, {key: 'ZMK', value: 'ZMK'}, {key: 'ZWD', value: 'ZWD'}]

### 

### export const  titlesList = [

###   {key: 'Mr', value: 'Mr'},

###   {key: 'Miss', value: 'Miss'},

###   {key: 'Ms', value: 'Ms'},

###   {key: 'Mrs', value: 'Mrs'},

###   {key: 'Lady', value: 'Lady'},

###   {key: 'Dr', value: 'Dr'},

###   {key: 'Sir', value: 'Sir'},

###   {key: 'Prof', value: 'Prof'},

###   {key: 'Mstr', value: 'Mstr'},

### ]

### 

### export let productTypeList = [

###   {

### \    key: '1',

### \    value: 'Hotel',

### \    suppliers: '9,27,19,113,77,40,116,90,16,45,117,34,61,25,42,41,79,30,28,20,50,5,84,73,75,71,47,11,78,64,103,6,49,8,74,48,63,150,52,53,33,97,115,99,1,100,114,13,4,76,102,10,39,2,112,7,190,88,130,132,153,192,151,191,152',

###   },

###   {

### \    key: '2',

### \    value: 'Ferry',

### \    suppliers: '91,35,62,105,118,98,93,106,6,108,37,36,89,94,95,401,121,400,122,123,124,125',

###   },

###   {

### \    key: '3',

### \    value: 'Activity',

### \    suppliers: '201,96,44,119,32,79,30,5,6,111,1,202,200,2,203',

###   },

###   {

### \    key: '4',

### \    value: 'Transfer',

### \    suppliers: '9,19,31,65,101,119,82,32,83,25,42,30,5,84,81,80,66,47,18,51,15,6,74,70,69,68,67,97,1,92,76',

###   },

###   {

### \    key: '5',

### \    value: 'Charge',

### \    suppliers: '',

###   },

###   {

### \    key: '7',

### \    value: 'Airfares',

### \    suppliers: '6,21,22,23,700',

###   },

###   {

### \    key: '8',

### \    value: 'Airfares Taxes',

### \    suppliers: '',

###   },

###   {

### \    key: '9',

### \    value: 'Adjustment',

### \    suppliers: '',

###   },

###   {

### \    key: '10',

### \    value: 'Cancellation Charge',

### \    suppliers: '',

###   },

###   {

### \    key: '11',

### \    value: 'Supplier Refund',

### \    suppliers: '',

###   },

###   {

### \    key: '12',

### \    value: 'Extraordinary Income',

### \    suppliers: '',

###   },

###   {

### \    key: '13',

### \    value: 'Change Fee',

### \    suppliers: '',

###   },

###   {

### \    key: '14',

### \    value: 'Agent Refund',

### \    suppliers: '',

###   },

### ]

### 

### export let addChargeStatus = [

###   {

### \    key: '67',

### \    value: 'account unbalanced',

###   },

###   {

### \    key: '30',

### \    value: 'amendment pending',

###   },

###   {

### \    key: '5',

### \    value: 'cancellation pending',

###   },

###   {

### \    key: '90',

### \    value: 'cancelled',

###   },

###   {

### \    key: '65',

### \    value: 'commission payable',

###   },

###   {

### \    key: '60',

### \    value: 'completed',

###   },

###   {

### \    key: '40',

### \    value: 'confirmed unpaid',

###   },

###   {

### \    key: '120',

### \    value: 'credit approved',

###   },

###   {

### \    key: '70',

### \    value: 'finalised',

###   },

###   {

### \    key: '20',

### \    value: 'instant purchase',

###   },

###   {

### \    key: '46',

### \    value: 'payment pending',

###   },

###   {

### \    key: '45',

### \    value: 'pending confirmation',

###   },

###   {

### \    key: '10',

### \    value: 'quote',

###   },

###   {

### \    key: '51',

### \    value: 'reconcile credit paid',

###   },

###   {

### \    key: '53',

### \    value: 'refund pending (agent)',

###   },

###   {

### \    key: '89',

### \    value: 'supplier cancellation',

###   },

###   {

### \    key: '55',

### \    value: 'supplier refund to EH',

###   },

###   {

### \    key: '50',

### \    value: 'supplier unpaid',

###   },

###   {

### \    key: '80',

### \    value: 'unavailable',

###   },

### ]

###
