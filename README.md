# work
สามารถก็อปปี้โค้ดนี้ เอาไปใส่ใน https://pdfmake.org/playground.html
var dd = {
    content: [
        { text: 'Made By Wongsatorn Naruroodganawaree', bold: true, fontSize: 12, alignment: 'center' , width: '*', noWrap: true, },
        { text: 'PDF Form Use Online', bold: true, fontSize: 12, alignment: 'center' , width: '*', noWrap: true, margin: [0, 0, 0, 4],},
        {
			table: {
				headerRows: 1,
				widths: ['50%', '50%'],
				// heights: ['80%', '80%'],
				body: [
				// 	[{text: 'Header 1', style: 'tableHeader'}, {text: 'Header 2', style: 'tableHeader'}],
					[
                        {
                            columns: [
                                {
                                    stack: [
                                        { text: 'PRIVATE STIRAGE / PUBLIC DONATION', fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        {
                                            width: 200,
                                            lineHeight: 1,
                                            table: {
                                                heights: [0, 0],
                                                widths: [61, 114],
                                                body: [
                                                    [{ text: 'Agreement No. #', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                                    { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] }]
                                                ]
                                            }
                                        },
                                        {
                                            width: 200,
                                            lineHeight: 1,
                                            table: {
                                                heights: [0, 0],
                                                widths: [45, 130],
                                                body: [
                                                    [{ text: 'Product ID #' , alignment: 'left', border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                                     { text: '', width: 0, alignment: 'center', border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0, 0] }]
                                                ]
                                            }
                                        },
                                        {
                                            width: 200,
                                            lineHeight: 1,
                                            table: {
                                                heights: [0],
                                                widths: ['auto'],
                                                body: [
                                                    [{ text: 'UCT/AM COLLECTION DATE & TIME:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, ]
                                                ]
                                            }
                                        },
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [150 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: 'TT / LT', width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },                                  
                                        { text: "MOTHER'S NAME", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        { text: "(ONLY FOR PRIVATE STORAGE)", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [180 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '0', preserveWhiteSpace: true, preserveLeadingSpaces: true,color: 'white' , width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },  
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [180 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '0', preserveWhiteSpace: true, preserveLeadingSpaces: true,color: 'white' , width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },
                                        { text: "PHYSICIAN / COLLECTOR NAME:", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [180 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '0', preserveWhiteSpace: true, preserveLeadingSpaces: true,color: 'white' , width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },  
                                        { text: "BIRTHING CENTRE NAME AND ADDRESS", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [180 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '0', preserveWhiteSpace: true, preserveLeadingSpaces: true,color: 'white' , width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },  
                                        {
                                            margin: [4, 0, 0 , 4],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [180 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '0', preserveWhiteSpace: true, preserveLeadingSpaces: true,color: 'white' , width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },
                                    ]
                                }
                            ]
                        },
                        {
                            columns: [
                                {
                                    stack: [
                                        {  
                                            table: {
                                                heights: [80],
                                                widths: ['100%'],
                                                body: [
                                                    [{ text: '', alignment: 'center' , border: [true, true, true, true], fontSize: 20, margin: [0, 5, 0, 0] }, ]
                                                ]
                                            }
                                        },
                                        {
                                            width: 200,
                                            lineHeight: 1,
                                            table: {
                                                heights: [0],
                                                widths: ['auto'],
                                                body: [
                                                    [{ text: 'UCT/AM PROCESSIBG DATE & TIME:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, ]
                                                ]
                                            }
                                        },
                                        {
                                            margin: [4, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [150 , 30],
                                                body: [
                                                    [{ text: '',  alignment: 'center' , border: [false, false, false, true], fontSize: 8 },
                                                     { text: '24 HRS', width: 0, alignment: 'left', border: [false, false, false, false], fontSize: 8}]
                                                ]
                                            }
                                        },
                                        { text: "CAUTION:", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 10, 0, 0] },
                                        { text: "NOT EVALUATED FOR INFECTIONS DISEASES", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 4, 0, 0] },
                                        { text: "ADCISE PATIENT OF COMMUINICABLE DISEASE RISKS", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] },
                                        
                                        { text: "PROCESSING FACILITY:", bold: true, fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 10, 0, 0] },
                                        { text: "REVIVA CELL THAILAND LTD.", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 4, 0, 0] },
                                        { text: "35/8 Moo 4, Khunkaew, Nakhonchaisri, NakhonPathom,", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] },
                                        { text: "73129, Thailand", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] },
                                        { text: "Phone: +66 (0)34312161", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] },
                                    ]
                                }
                            ]
                        },
					]
				]
			}
        },
        
        {
			table: {
				headerRows: 1,
				widths: ['50%', '50%'],
				// heights: ['80%', '80%'],
				body: [
				// 	[{text: 'Header 1', style: 'tableHeader'}, {text: 'Header 2', style: 'tableHeader'}],
					[
                        {
                            columns: [
                                {
                                    stack: [
                                        { text: 'UNIT INFORMATION', fontSize: 8, bold: true ,alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                        { text: 'In Process Umbilical Cord / Amnion Tissue Product ID #', alignment: 'center' , fontSize: 8, width: '*', noWrap: true, margin: [12, 4, 0, 0] },
                                        {  
                                            margin: [0, 4, 0 , 0],
                                            table: {
                                                heights: [50],
                                                widths: ['100%'],
                                                body: [
                                                    [{ text: '', alignment: 'center' , border: [true, true, true, true], fontSize: 20, margin: [0, 5, 0, 0] }, ]
                                                ]
                                            }
                                        },
                                        { text: 'Product Division Code: Fr', alignment: 'center' , fontSize: 8, width: '*', noWrap: true, margin: [0, 8, 0, 8] },
                                        {
                                            margin: [0, 0, 0 , 0],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0 , 0 ,0 ],
                                                widths: [78 , 5 , 55 , 5],
                                                body: [
                                                    [  
                                                        { text: "CRYOPRESERVED UCT", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [0, 2, 0, 0] , border: [false, false, false, false], },
                                                        { svg: '<svg width="8" height="8"><rect width="8" height="8" style="fill:white;stroke:black;stroke-width:1" /></svg>',border: [false, false, false, false], margin: [0, 2, 0, 0] },
                                                        { text: "AMNION TISSUE", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [0, 2, 0, 0] , border: [false, false, false, false], },
                                                        { svg: '<svg width="8" height="8"><rect width="8" height="8" style="fill:white;stroke:black;stroke-width:1" /></svg>',border: [false, false, false, false], margin: [0, 2, 0, 0] },
                                                    
                                                    ]
                                                ]
                                            }
                                        },                                        
                                        {
                                            width: 200,
                                            lineHeight: 1,
                                            table: {
                                                heights: [0, 0],
                                                widths: [112, 114],
                                                body: [
                                                    [{ text: 'DATE OF CRYOPRESERVATION:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                                    { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] }]
                                                ]
                                            }
                                        },
                                        { text: 'CRYOPRESERVED UCT/AM ≤ 150°C IN 10% DMSO (V/V)', fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 5, 0, 0] },
                                    ]
                                }
                            ]
                        },
                        {
                            columns: [
                                {
                                    stack: [
                                        { text: "IMPORTANT INFORMATION", bold: true,fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 10, 0, 0] },
                                        { text: "STORE AT s-150°C OR LOWER TEMPERATURE", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 4, 0, 0] },
                                        { text: "DO NOT IRRADIATE / DO NOT X-RAY", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] },
                                        
                                        { text: "NO EXPIRATION DATE", bold: true,fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 10, 0, 0] },
                                        {
                                            margin: [4, 16, 0 , 4],
                                            lineHeight: 1,
                                            table: {
                                                heights: [0 , 0],
                                                widths: [0 , 0],
                                                body: [
                                                    [{ svg: '<svg width="8" height="8"><rect width="8" height="8" style="fill:white;stroke:black;stroke-width:1" /></svg>',border: [false, false, false, false], margin: [0, 2, 0, 0] },
                                                    { text: "FOR THE PURPOSE OF MSC (WJ)/MSC(AM) ISOLATION", fontSize: 8, alignment: 'left', width: '*', noWrap: true, margin: [5, 2, 0, 0] , border: [false, false, false, false], },]
                                                ]
                                            }
                                        },
                                    ]
                                }
                            ]
                        },
					]
				]
			}
        },
        {
            columns: [
                {
                    stack: [
                        {
                            margin: [0, 10, 0, 10],
                            width: 200,
                            lineHeight: 1,
                            table: {
                                heights: [0, 0, 0, 0 ,0],
                                widths: [53, 114 , 155 , 22 , 114],
                                body: [
                                        [
                                            { text: 'PREPARED BY:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                            { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] },
                                            { text: '', width: '*', border: [false, false, false, false], noWrap: true, },
                                            { text: 'DATE:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                            { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] }
                                        ]
                                ]
                            }
                        },
                        {
                            width: 200,
                            lineHeight: 1,
                            table: {
                                heights: [0, 0, 0, 0 ,0],
                                widths: [85, 82 , 155 , 22 , 114],
                                body: [
                                        [
                                            { text: 'SUPERVISORY REVIEW:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                            { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] },
                                            { text: '', width: '*', border: [false, false, false, false], noWrap: true, },
                                            { text: 'DATE:', alignment: 'left' , border: [false, false, false, false], fontSize: 8, margin: [0, 5, 0, 0] }, 
                                            { text: '',  width: 0, alignment: 'center' , border: [false, false, false, true], fontSize: 8, margin: [0, 5, 0 , 0] }
                                        ]
                                ]
                            }
                        },
                    ]
                }
            ]
        },    
        {
            margin: [0, 210, 0, 10],
            table: {
                heights: [0],
                widths: ['100%'],
                body: [
                    [{ text: '', border: [false, true, false, false] }
                    ]
                ]
            }
        },
        {
            columns: [
                { text: 'RTL/FORM G.1-3 Rev. B', width: 'auto', fontSize: 8, noWrap: true, margin: [15, 0, 0, 0] },

                { text: '', width: '*', fontSize: 8, noWrap: true, },

                { text: 'Issue date: 01 Nov 2020', width: 'auto', fontSize: 8, noWrap: true, margin: [0, 0, 15, 0] },
            ]
        },
        {
            columns: [
                { text: '', width: 'auto', fontSize: 8, noWrap: true, },

                { text: '', width: '*', fontSize: 8, noWrap: true, },

                { text: 'Reviva Cell Thailand Ltd., 35/8 Moo 4, Khunkaew, Nakhonchaisri, Nakhonpathom, 73120, Thailand', width: 'auto', fontSize: 8, noWrap: true, margin: [0, 4, 0, 0] },

                { text: '', width: '*', fontSize: 8, noWrap: true, },

                { text: '', width: 'auto', fontSize: 8, noWrap: true, },
            ]
        },
        { text: '', width: '*', fontSize: 8, noWrap: true},
    ],
}
