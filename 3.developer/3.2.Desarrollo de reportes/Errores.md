1. {"pdf_error": "Extra content at the end of the document, line 9, column 1", "success": false, "error": "Ocurri\u00f3 un error inesperado. Por favor contacte a soporte."}

	Este error suele suceder cuando el código correspondiente a HEADER, STYLE, BODY, FOODER se encuentra en otro campo, por ejemplo, el código correspondiente a HEADER se encuentra en BODY.

2. {"pdf_error": "list index out of range\nspanning problem in 
	<Table@0x7FD37E0ABB40 1 rows x 4 cols(tallest row 18)>
    with cell(0,0) containing\nu'<Z3CParagraph at 0x7fd37e0890a0>Im\\xe1gen' hmax=1 lim=1 avail=538.582677165 x 737.007874016\nH0=[None] H=[18]\nspanCons={(0, 1): 18}", "success": false, "error": "Ocurri\u00f3 un error inesperado. Por favor contacte a soporte."}
	Este error surgió porque se aplicó el estilo ```<blockSpan start="1,1" stop="2,0" /> ``` el problema es que se hizo referencia a una fila que no existtía, ya que la tabla en donde se aplicó el estilo solo contaba con una fila.
	