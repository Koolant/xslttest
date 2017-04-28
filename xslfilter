<xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
  <xsl:output omit-xml-declaration="yes" indent="yes"/>
  <xsl:template match="/">
    <xsl:variable name="record" select="//record"/>
<xsl:variable name="largest" select="$record[not(//./codice_cliente > codice_cliente)][1]"/>
    <result>
      <solution>
<xsl:for-each select="$largest">
        <xsl:value-of select="$largest/codice_cliente"/>
      </xsl:for-each>
      </solution>
    </result>
  </xsl:template>
</xsl:stylesheet>
