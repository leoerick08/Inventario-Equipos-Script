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

</div>

<p>Copyright (c) 2025, @leoerick08</p>
