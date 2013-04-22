<?xml version="1.0" encoding="UTF-8"?>
<xsl:stylesheet version="2.0"
  xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
  <xsl:output method="xml" version="1.0" encoding="utf-8" indent="yes" />
  <!-- Lisbona WeaGoo -->
  <!-- Starting template to generate all the other structures -->
	<xsl:template match="@*|node()">
		<xsl:copy>
			<xsl:apply-templates select="@*|node()" />
		</xsl:copy>
	</xsl:template>

	<!-- Configure shortName for submission on Android -->
	<xsl:template match="//application[1]/@shortName">
		<xsl:attribute name="shortName">Lisbonaunaguidautile</xsl:attribute>
	</xsl:template>

	<xsl:template match="categories/category[@key='root']/categories">
		<xsl:copy>
		<xsl:apply-templates select="attribute::*" />
		<!-- La Città -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjpBww']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>
		<!-- Cosa Vedere -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww']">
			<xsl:copy>
			<xsl:attribute name="listtype">-1</xsl:attribute>
			<xsl:attribute name="stringlisttype">catlist</xsl:attribute>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='listtype')][not(name()='stringlisttype')][not(name()='parentKey')] | child::* [not(name()='objects')]" />
			<xsl:element name="categories">
			<!-- palazzi -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiJJww']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- chiese -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjxLgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- vie -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj5VQw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- musei -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjZNgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- strutture -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjBPgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- monumenti -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjCPgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- teatri -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjTDww']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- castelli -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRipRgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- parchi giardini -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiiHww']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- parchi divertimenti -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIQsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRgMDA']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- campi da golf -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjyLgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- luoghi naturalistici -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiRTgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- luoghi storici -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjqBww']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRihHww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>


			</xsl:element>
			</xsl:copy>
		</xsl:for-each>

		<!-- Storie e Curiosità -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRi0ywEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>


		<!-- Itinerari -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj6Fww']">
				<xsl:copy>
				<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>

		<!-- Fuori porta -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjzLgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>

		<!-- Cosa fare -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw']">
			<xsl:copy>
			<xsl:attribute name="listtype">-1</xsl:attribute>
			<xsl:attribute name="stringlisttype">catlist</xsl:attribute>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='listtype')][not(name()='stringlisttype')][not(name()='parentKey')] | child::* [not(name()='objects')]" />
			<xsl:element name="categories">
			<!-- Eventi e Festival -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRigfQw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>			
			<!-- Shopping e Mercati -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjh2gEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
            <!-- la sera -->
				<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRirywEM']">
					<xsl:copy>
					<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
					<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
					</xsl:copy>
			</xsl:for-each>
			<!-- Relax e divertimenti -->
				<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj9hAEM']">
					<xsl:copy>
					<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
					<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
					</xsl:copy>
				</xsl:for-each>
			<!-- Con i bambini-->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjAlQEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- Natale e festività -->
				<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRi-dQw']">
					<xsl:copy>
					<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjaNgw</xsl:attribute>
					<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
					</xsl:copy>
				</xsl:for-each>
         </xsl:element>
		</xsl:copy>
		</xsl:for-each>

		<!-- Come Muoversi -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjSDww']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>
		
		<!-- Servizi geo-localizzati -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww']">
			<xsl:copy>
			<xsl:attribute name="listtype">-1</xsl:attribute>
			<xsl:attribute name="stringlisttype">catlist</xsl:attribute>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='listtype')][not(name()='stringlisttype')][not(name()='parentKey')] | child::* [not(name()='objects')]" />
			<xsl:element name="categories">
			<!-- Uffici info turistiche -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjDwwEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- trasporti -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjDPgw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- ospedali -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRibdQw']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- vigili urbani -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiUpAEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- polizia di stato -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiTpAEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- vigili del fuoco -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiSpAEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			<!-- parcheggi -->
			<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjeswEM']">
				<xsl:copy>
				<xsl:attribute name="parentKey">ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRj7Fww</xsl:attribute>
				<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
				</xsl:copy>
			</xsl:for-each>
			</xsl:element>
			</xsl:copy>
		</xsl:for-each>
		<!-- Dove Mangiare -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjEPgw']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>

		<!-- Dove Mangiare -Gluten free-->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjJ4gEM']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>		

		<!-- Hotel con Booking -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIwsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRjBtQMM']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>
		<!-- Le altre guide di weagoo -->
		<xsl:for-each select="//category[@key='ahJzfm1hcDJhcHAtcGxhdGZvcm1yIgsSC1VzZXJBY2NvdW50GKiLWgwLEghDYXRlZ29yeRiKJww']">
			<xsl:copy>
			<xsl:attribute name="parentKey"><xsl:value-of select="../../@key"/></xsl:attribute>
			<xsl:apply-templates select="attribute::* [not(name()='parentKey')] | child::* " />
			</xsl:copy>
		</xsl:for-each>
		</xsl:copy>
	</xsl:template>
</xsl:stylesheet>
