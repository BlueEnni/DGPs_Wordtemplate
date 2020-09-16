C:\Users\***\AppData\Roaming\Microsoft\Templates\LiveContent\16\User\Word Document Bibliography Styles
3566 Literaturverzeichnis mit Edition und Auflage
3940 ???
7001 Templates

<xsl:variable name="i_					Ausgaben
<xsl:template name="templ_prop_			Operators/Seperators


templ_prop_Dot

1606
  <xsl:template name="templ_prop_Dot" >
    <xsl:param name="LCID" />
    <xsl:variable name="_LCID">
      <xsl:call-template name="localLCID">
        <xsl:with-param name="LCID" select="$LCID"/>
      </xsl:call-template>
    </xsl:variable>
    <xsl:value-of select="/*/b:Locals/b:Local[@LCID=$_LCID]/b:General/b:Dot"/>
  </xsl:template>
