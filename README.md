<div>
    <p style="margin-top:0pt; margin-bottom:8pt;"></p>
    <hr size="1" align="center" style="width:100%; color:#f8faff; background-color:#f8faff;">
    <p></p>
    <table cellspacing="0" cellpadding="0" style="border: 0.75pt solid rgb(153, 153, 153); border-collapse: collapse; width: 100%;">
        <tbody>
            <tr>
                <td style="border-right:0.75pt solid #999999; border-bottom:1.5pt solid #666666; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>T&iacute;tulo</strong></p>
                </td>
                <td style="border-left:0.75pt solid #999999; border-bottom:1.5pt solid #666666; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Documentaci&oacute;n del Script de Inventario de Equipos de C&oacute;mputo</strong></p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Autor</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">Erick Anthony Calle Sulca</p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Fecha</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">14 de febrero del 2025</p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Versi&oacute;n</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">v1.0</p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Organizaci&oacute;n</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">Soporte TI</p>
                </td>
            </tr>
        </tbody>
    </table>
    <div align="center">
        <hr size="1" align="center" style="width:100%; color:#f8faff; background-color:#f8faff;">
    </div>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Resumen Ejecutivo</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">Este documento describe el desarrollo, implementaci&oacute;n y resultados del <strong>Script de Inventario de Equipos de C&oacute;mputo</strong>, una herramienta automatizada dise&ntilde;ada para optimizar el proceso de recopilaci&oacute;n de informaci&oacute;n t&eacute;cnica de los equipos en los laboratorios de c&oacute;mputo. El script reduce el tiempo de inventariado en un 50%, minimiza errores humanos y facilita la actualizaci&oacute;n del inventario. Fue desarrollado en lenguaje Batch (BAT) y se ejecuta en sistemas Windows, generando un archivo de texto con los datos recopilados.</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>1. Introducci&oacute;n</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Contexto</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">En el departamento de soporte t&eacute;cnico, el proceso de inventariado de equipos de c&oacute;mputo se realizaba manualmente, lo que implicaba una verificaci&oacute;n f&iacute;sica de cada equipo y la transcripci&oacute;n de datos como el nombre del equipo, modelo, n&uacute;mero de serie, direcci&oacute;n MAC, especificaciones de hardware y software. Este proceso era repetitivo, propenso a errores y consum&iacute;a una cantidad significativa de tiempo.</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Objetivo</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">El objetivo del script es <strong>automatizar la recopilaci&oacute;n de informaci&oacute;n t&eacute;cnica de los equipos</strong>, permitiendo a los t&eacute;cnicos enfocarse en tareas m&aacute;s cr&iacute;ticas. El script obtiene autom&aacute;ticamente los datos del sistema y solicita &uacute;nicamente la informaci&oacute;n que no puede ser recopilada de manera automatizada, como la ubicaci&oacute;n del equipo y la serie del monitor.</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Alcance</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">El script se utiliza en los laboratorios de c&oacute;mputo para inventariar equipos con sistemas operativos Windows. Es ejecutado por los t&eacute;cnicos desde un USB y genera un archivo de texto con la informaci&oacute;n recopilada.</p>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>2. Desarrollo del Script</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Tecnolog&iacute;as Utilizadas</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Lenguaje</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Batch (BAT).</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Herramientas</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Comandos de Windows (wmic,</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">reg query,</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">getmac).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Funcionalidades Principales</strong></p>
    <ol type="1" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;"><strong>Recopilaci&oacute;n autom&aacute;tica de datos</strong>:<ul type="circle" style="margin-right:0pt; margin-left:0pt; padding-left:0pt;">
                <li style="margin-left:29pt; margin-bottom:8pt; line-height:116%; padding-left:7pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Nombre del equipo, marca, modelo, n&uacute;mero de serie, direcci&oacute;n MAC, procesador, disco duro, RAM, versi&oacute;n de Windows y versi&oacute;n de Office.</span></li>
            </ul>
        </li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;"><strong>Entrada manual de datos</strong>:<ul type="circle" style="margin-right:0pt; margin-left:0pt; padding-left:0pt;">
                <li style="margin-left:29pt; margin-bottom:8pt; line-height:116%; padding-left:7pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Ubicaci&oacute;n del equipo y serie del monitor.</span></li>
            </ul>
        </li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;"><strong>Generaci&oacute;n de archivo de texto</strong>:<ul type="circle" style="margin-right:0pt; margin-left:0pt; padding-left:0pt;">
                <li style="margin-left:29pt; margin-bottom:8pt; line-height:116%; padding-left:7pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">La informaci&oacute;n recopilada se guarda en un archivo de texto con el nombre de la ubicaci&oacute;n ingresada.</span></li>
            </ul>
        </li>
    </ol>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>C&oacute;digo Fuente&nbsp;</strong>batch</p>
    <table cellspacing="0" cellpadding="0" style="border: 0.75pt solid rgb(0, 0, 0); border-collapse: collapse; width: 100%;">
        <tbody>
            <tr>
                <td style="width:413.9pt; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">@echo off</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">set /p ubicacion=</span></em> <em><span style="font-family:'Franklin Gothic Book';">UBICACION-SERIE DEL MONITOR:</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo HOSTNAME: %computername% &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo MARCA &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic csproduct get vendor &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo MODELO &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic csproduct get name &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo NUMERO SERIE &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic bios get serialnumber &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo MAC &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">getmac &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo PROCESADOR &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">WMIC /Output:STDOUT CPU get Name &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo DISCO DURO &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic diskdrive get Caption,size,MediaType &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo RAM &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic MemoryChip get Capacity,PositionInRow &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo VERSION WINDOWS &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">wmic os get Caption &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">echo VERSION OFFICE &gt;&gt; &quot;%ubicacion%.txt&quot;</span></em></p>
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><em><span style="font-family:'Franklin Gothic Book';">reg query &quot;HKEY_CLASSES_ROOT\Word.Application\CurVer&quot; &gt;&gt; &quot;%ubicacion%.txt&rdquo;</span></em></p>
                </td>
            </tr>
        </tbody>
    </table>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;">La informaci&oacute;n que se obtiene es el siguiente:</p>
    <table cellspacing="0" cellpadding="0" style="width:439.95pt; border:1pt solid #999999; border-collapse:collapse;">
        <tbody>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1.5pt solid #666666; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; text-indent:72pt; font-size:12pt;"><strong>Secci&oacute;n</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1.5pt solid #666666; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; text-indent:72pt; font-size:12pt;"><strong>Descripci&oacute;n</strong></p>
                </td>
            </tr>
            <tr style="height:17pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>HOSTNAME</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Nombre del equipo en la red.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>MARCA</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Fabricante del equipo.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>MODELO</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Modelo espec&iacute;fico del equipo.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>NUMERO SERIE</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">N&uacute;mero de serie &uacute;nico del equipo.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>MAC</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Direcciones MAC de las interfaces de red.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>PROCESADOR</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Modelo del procesador.</p>
                </td>
            </tr>
            <tr style="height:32.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>DISCO DURO</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Informaci&oacute;n sobre los discos duros y dispositivos de almacenamiento.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>RAM</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Capacidad de la memoria RAM instalada.</p>
                </td>
            </tr>
            <tr style="height:32.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>VERSION WINDOWS</strong></p>
                </td>
                <td style="width:297.75pt; border-bottom:1pt solid #999999; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Versi&oacute;n del sistema operativo Windows instalado.</p>
                </td>
            </tr>
            <tr style="height:16.5pt;">
                <td style="width:127.2pt; border-right:1pt solid #999999; padding-right:3pt; padding-left:3pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;"><strong>VERSION OFFICE</strong></p>
                </td>
                <td style="width:297.75pt; padding-right:3pt; padding-left:3.5pt; vertical-align:middle;">
                    <p style="margin-top:0pt; margin-bottom:0pt; font-size:12pt;">Versi&oacute;n de Microsoft Office instalada.</p>
                </td>
            </tr>
        </tbody>
    </table>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>3. Implementaci&oacute;n</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Requisitos</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Sistema operativo</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Windows 7 o superior.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Permisos</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Ejecuci&oacute;n con permisos de perfil est&aacute;ndar o administrador.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Herramientas</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: USB con el script y carpeta de destino para los archivos generados.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Proceso de Uso</strong></p>
    <ol type="1" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;">Conectar el USB al equipo.</li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;">Ejecutar el script (inventario de equipos.bat).</li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;">Ingresar la ubicaci&oacute;n del equipo cuando se solicite.</li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;">Ingresar la serie del monitor cuando se solicite.</li>
        <li style="margin-left:33.01pt; margin-bottom:8pt; padding-left:2.99pt;">Recuperar el archivo de texto generado en la misma ruta donde se ejecut&oacute; el script.</li>
    </ol>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Distribuci&oacute;n</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">El script se distribuye en un USB que contiene:</p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">El archivo</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">inventario de equipos.bat.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Una carpeta para almacenar los archivos generados.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>4. Resultados y Beneficios</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Resultados</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Reducci&oacute;n del tiempo de inventariado</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: El tiempo dedicado a esta tarea se redujo en un 50%.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Menos errores humanos</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: La automatizaci&oacute;n minimiz&oacute; los errores de transcripci&oacute;n.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Inventario m&aacute;s consistente</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Los datos recopilados son precisos y estandarizados.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Beneficios</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Eficiencia</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Los t&eacute;cnicos pueden enfocarse en tareas m&aacute;s cr&iacute;ticas.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Facilidad de uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: El script es intuitivo y f&aacute;cil de ejecutar.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Actualizaci&oacute;n en tiempo real</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Los archivos generados permiten mantener el inventario actualizado.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>5. Conclusiones</strong></p>
    <p style="margin-top:0pt; margin-bottom:8pt;">El <strong>Script de Inventario de Equipos de C&oacute;mputo</strong> ha demostrado ser una soluci&oacute;n efectiva para optimizar el proceso de inventariado en los laboratorios de c&oacute;mputo. Su implementaci&oacute;n ha permitido ahorrar tiempo, reducir errores y mejorar la precisi&oacute;n de los datos recopilados. Este proyecto es un ejemplo de c&oacute;mo la automatizaci&oacute;n puede transformar procesos manuales en tareas eficientes y confiables.</p>
    <p style="margin-top:0pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>6. Anexos</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:28.52pt; margin-bottom:8pt; padding-left:7.48pt; font-family:serif;"><strong><span style="font-family:Aptos;">C&oacute;digo Completo</span></strong></li>
    </ul>
    <p style="margin-top:0pt; margin-bottom:8pt; text-indent:18pt;">Incluido en la secci&oacute;n <strong>2. Desarrollo del Script</strong>.</p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:28.52pt; margin-bottom:8pt; padding-left:7.48pt; font-family:serif;"><strong><span style="font-family:Aptos;">Ejemplo de Archivo de Salida</span></strong></li>
    </ul>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">HOSTNAME: PC-001</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">MARCA: Dell Inc.</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">MODELO: OptiPlex 7070</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">NUMERO SERIE: ABC123456</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">MAC: 00-1A-2B-3C-4D-5E</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">PROCESADOR: Intel(R) Core(TM) i7-8700 CPU @ 3.20GHz</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">DISCO DURO: Samsung SSD 860 EVO 500GB</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">RAM: 16 GB</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">VERSION WINDOWS: Windows 10 Pro</p>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">VERSION OFFICE: Word.Application.16</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>Capturas de Pantalla</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Ejecuci&oacute;n del script.</span></li>
    </ul>
    <ol type="1" class="awlist1" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:36pt; text-indent:-18pt;"><span style="width:7.33pt; font:7pt 'Times New Roman'; display:inline-block;">&nbsp; &nbsp; &nbsp;</span>Abrimos el script que se encuentra en la carpeta del laboratorio de c&oacute;mputo en nuestro USB con clic derecho &gt; abrir.</li>
        <li style="margin-left:36pt; text-indent:-18pt;"><span style="width:7.33pt; font:7pt 'Times New Roman'; display:inline-block;">&nbsp; &nbsp; &nbsp;</span>Nos aparece la siguiente ventana.&nbsp;</li>
        <li style="margin-left:36pt; text-indent:-18pt;"><span style="width:7.33pt; font:7pt 'Times New Roman'; display:inline-block;">&nbsp; &nbsp; &nbsp;</span>Colocaremos la ubicaci&oacute;n del equipo a hacer inventario, en este caso se encuentra en la posici&oacute;n &ldquo;1&rdquo; y luego colocamos la serie manualmente del monitor, luego finalizamos presionando la tecla enter.</li>
        <li style="margin-left:36pt; margin-bottom:8pt; text-indent:-18pt;"><span style="width:7.33pt; font:7pt 'Times New Roman'; display:inline-block;">&nbsp; &nbsp; &nbsp;</span>Esperamos que se cierre la ventana del batch y autom&aacute;ticamente nos generara el archivo texto con toda la informaci&oacute;n actual del equipo.</li>
    </ol>
    <p style="margin-top:0pt; margin-left:18pt; margin-bottom:8pt;">&nbsp; &nbsp;</p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Archivo de texto generado.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">Explicaci&oacute;n de los datos obtenidos del script ejecutado:</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>1. HOSTNAME</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Es el nombre del equipo en la red.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">UTP388910.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Identifica de manera &uacute;nica el equipo en la red o en el inventario.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>2. MARCA</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Indica el fabricante del equipo.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">H P</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(HP).</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Es &uacute;til para saber el fabricante del hardware (por ejemplo, HP, Dell, Lenovo).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>3. MODELO</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Especifica el modelo del equipo.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">H P P r o M i n i 4 0 0 G 9 D e s k t o p P C.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Proporciona detalles sobre el modelo espec&iacute;fico del equipo (por ejemplo, HP Pro Mini 400 G9).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>4. NUMERO SERIE</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Es el n&uacute;mero de serie &uacute;nico del equipo.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">8 C C 3 0 5 2 3 K L.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Es &uacute;til para identificar de manera &uacute;nica el hardware, especialmente en garant&iacute;as o soporte t&eacute;cnico.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>5. MAC</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Muestra las direcciones MAC de las interfaces de red del equipo.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valores</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span>
            <ul type="circle" style="margin-right:0pt; margin-left:0pt; padding-left:0pt;">
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">50-5A-65-94-96-6D</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Medios desconectados).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">50-5A-65-94-96-D5</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Asociada a</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">\Device\Tcpip_{...}).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">7C-4D-8F-99-A1-40</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Medios desconectados).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">00-50-56-C0-00-01</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Asociada a</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">\Device\Tcpip_{...}).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">00-50-56-C0-00-08</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Asociada a</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">\Device\Tcpip_{...}).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">0A-00-27-00-00-10</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">(Asociada a</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">\Device\Tcpip_{...}).</span></li>
            </ul>
        </li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Las direcciones MAC son identificadores &uacute;nicos de las tarjetas de red. Son &uacute;tiles para la gesti&oacute;n de redes y la identificaci&oacute;n de dispositivos.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>6. PROCESADOR</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Especifica el modelo del procesador.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">1 2 t h G e n I n t e l ( R ) C o r e ( T M ) i 7 - 1 2 7 0 0 T.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Proporciona informaci&oacute;n sobre la CPU del equipo (por ejemplo, un Intel Core i7-12700T de 12&ordf; generaci&oacute;n).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>7. DISCO DURO</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Muestra informaci&oacute;n sobre los discos duros y dispositivos de almacenamiento conectados.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valores</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span>
            <ul type="circle" style="margin-right:0pt; margin-left:0pt; padding-left:0pt;">
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">K I N G S T O N S N V 2 S 5 0 0 G: Disco duro fijo de 500 GB.</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">K i n g s t o n D a t a T r a v e l e r 3 . 0 U S B D e v i c e: Dispositivo USB de 3094 MB (aprox. 3 GB).</span></li>
                <li style="margin-left:29pt; margin-bottom:8pt; padding-left:7pt;"><span style="line-height:116%; font-family:Aptos; font-size:12pt;">S T 1 0 0 0 L M 0 4 9 - 2 G H 1 7 2: Disco duro fijo de 1000 GB (1 TB).</span></li>
            </ul>
        </li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Proporciona detalles sobre la capacidad y el tipo de almacenamiento disponible en el equipo.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>8. RAM</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Indica la capacidad de la memoria RAM instalada.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">1 7 1 7 9 8 6 9 1 8 4</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">bytes (16 GB).</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Muestra la cantidad de memoria RAM disponible en el equipo.</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>9. VERSION WINDOWS</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Especifica la versi&oacute;n del sistema operativo Windows instalado.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">M i c r o s o f t W i n d o w s 1 0 P r o E d u c a t i o n.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Proporciona informaci&oacute;n sobre la edici&oacute;n y versi&oacute;n de Windows (por ejemplo, Windows 10 Pro Education).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;"><strong>10. VERSION OFFICE</strong></p>
    <ul type="disc" style="margin:0pt; padding-left:0pt;">
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Descripci&oacute;n</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Indica la versi&oacute;n de Microsoft Office instalada.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Valor</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">:</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Word.Application.16.</span></li>
        <li style="margin-left:27.6pt; margin-bottom:8pt; line-height:116%; padding-left:8.4pt; font-family:serif; font-size:10pt;"><strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Uso</span></strong><span style="line-height:116%; font-family:Aptos; font-size:12pt;">: Muestra la versi&oacute;n de Office (en este caso, Office 2016 o superior, ya que</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">Word.Application.16</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">&nbsp;</span><span style="line-height:116%; font-family:Aptos; font-size:12pt;">corresponde a Office 2016/2019/2021).</span></li>
    </ul>
    <p style="margin-top:0pt; margin-left:36pt; margin-bottom:8pt;">&nbsp;</p>
    <p style="margin-top:0pt; margin-bottom:8pt;"><strong>7. Glosario (opcional)</strong></p>
    <table cellspacing="0" cellpadding="0" style="border: 0.75pt solid rgb(153, 153, 153); border-collapse: collapse; width: 100%;">
        <tbody>
            <tr>
                <td style="border-right:0.75pt solid #999999; border-bottom:1.5pt solid #666666; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>T&eacute;rmino</strong></p>
                </td>
                <td style="border-left:0.75pt solid #999999; border-bottom:1.5pt solid #666666; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Definici&oacute;n</strong></p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Batch (BAT)</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">Lenguaje de scripting utilizado en Windows para automatizar tareas.</p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>WMIC</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; border-bottom:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">Herramienta de l&iacute;nea de comandos de Windows para obtener informaci&oacute;n del sistema.</p>
                </td>
            </tr>
            <tr>
                <td style="border-top:0.75pt solid #999999; border-right:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;"><strong>Inventario</strong></p>
                </td>
                <td style="border-top:0.75pt solid #999999; border-left:0.75pt solid #999999; padding-right:5.03pt; padding-left:5.03pt; vertical-align:top;">
                    <p style="margin-top:0pt; margin-bottom:8pt; line-height:116%; font-size:12pt;">Proceso de recopilaci&oacute;n y registro de informaci&oacute;n sobre los equipos de c&oacute;mputo.</p>
                </td>
            </tr>
        </tbody>
    </table>
    <div align="center">
        <hr size="1" align="center" style="width:100%; color:#f8faff; background-color:#f8faff;">
    </div>
    <p style="margin-top:0pt; margin-bottom:8pt;"><br></p>
</div>
Copyright (c) 2025, @leoerick08
