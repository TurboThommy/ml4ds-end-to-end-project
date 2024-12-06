# ml4ds-end-to-end-project

## Bedeutung der Spalten aus den Eingabedateien

### RPAKREP_VEHICLE_HKEY

ID der Zeilen

### COMPANY

### OFFICE

Kennung einer spezifischen Niederlassung von Emil Frey

### OFFICE_MAIN_BRAND

Kürzel der Hauptautomarke der Niederlassung

### CHASSIS_NUMBER

Fahrgestellnummer

### MANUFACTURER_SHORT

Kürzel des Herstellers des Fahrzeugs

### MANUFACTURER

Herstellerbezeichnung ausgeschrieben (Automarke)

### VEHICLE_GROUP

Modellreihe der das Fahrzeug zugehörig ist

### VEHICLE_TYPE

Genaue Modellbezeichnung des Fahrzeugs

### MODEL_CODE

Von den knapp 99.000 Zeilen enthalten etwa 72.000 Zeilen einen Wert aus 5.000 verschiedenen MODEL_CODEs. Die verbleibenden rund 27.000 Zeilen haben einen leeren Wert.

### VARIANT

Ist nicht eindetig, größtenteils leere Einträge

### MILEAGE

Kilometerstand

### OPERATING_HOURS

Fast ausschließlich 0en, es gibt einige wenige andere Werte

### MILAGE_IN_FIELD

Enthält 1en oder leere Einträge

### MILAGE_SALES

Kilometerstand zum Zeitpunkt des Ankaufs

### OPERATING_HOURS_SALES

Irrelevant, siehe OPERATING_HOURS

### RIM_KEY

Hat unter 20 Varianten, großteil leer

### COLOR_CODE

Vermutlich abhängig von COLOR

### COLOR_CODE_NAME

Vermutlich abhängig von COLOR

### COLOR

Farbe des Autos

### COLOR_TYPE

Vermutlich abhängig von COLOR

### UPHOLSTERY_CODE

ID der Polsterung

### UPHOLSTERY

Polsterung

### UPHOLSTERY_CODE_ALT

Irrelevant

### CERTIFICATE_TYPE

-

### CERTIFICATE_TYPE_DATE

Irrelevant

### FACTORY_NUMBER

-

### ENGINE_ID

Motor-ID

### ENGINE_TYPE

Freitextfeld? des Motortyps

### ENGINE_ID_ALT

Irrelevant

### TRANSMISSION

Größtenteils leer

### TRANSMISSION_TYPE

Art des Getriebes

### TRANSMISSION_ID

Größtenteils leer

### TRANSMISSION_SHORT

Kurznamen für Gruppierungen von Getrieben

### TRANSMISSION_NAME

Scheint abhängig von TRANSMISSION_SHORT zu sein

### RIMS

Felgen

### FRONT_TIRES

Vorderreifen

### FRONT_TIRES_CONDITION

Irrelevant

### REAR_TIRES

Hinterreifen

### REAR_TIRES_CONDITION

Irrelevant

### NUMBER_DOORS

Anzahl Türen

### NUMBER_SEATS

Anzahl Sitze

### PERMITTED_TOTAL_WEIGHT

Maximales Gesamtgewicht?

### MAX_TRAILOR_LOAD

Maximale Anhängerlast

### CURB_WEIGHT

Leergewicht

### YEAR_CONSTRUCTION

Baujahr

### CONSTRUCTION_MONTH

Buamonat

### NUMBER_AXLE

Anzahl der Achsen

### NUMBER_ENGINE_CYLINDER

Zylinderanzahl im Motor

### REPAIR_RKZ

Irrelevant

### OPTICAL_CONDITION

Irrelevant

### TECHNICAL_CONDITION

Irrelevant

### ACCIDENT_VEHICLE

Bool: Ist Unfallfahrzeug (Konvertierung zu Bool muss noch ausgeführt werden)

### COMMISSION_NUMBER

Auftragsnummer

### HORSEPOWER

Leistung (in PS)

### KW

Leistung (in KW)

### CCM

Hubraum

### NUMBER_OWNERS

Anzahl Vorbesitzer

### IS_USED_CAR

Gebrauchtwagen ja/nein (wird teilweise durch COMMISSION_TYPE) abgebildet

### LEASING_CONTRACT_DATE

Zeitpunkt, zu welchem ein Leasingvertrag für da Auto abgeschlossen wurde

### LEASING_START

Beginn der Laufzeit des Leasingvertrags

### LEASING_END

Ende der Laufzeit des Leasingvertrags

### LEASING_MILAGE

Laufleistung, welche der Leasingvertrag umfasst

### PAINT_TYPE

ABSOLUT IRRELEVANT

### FINANCING_TYPE

Nr. des FINANCING_TYPE_NAME

### FINANCING_TYPE_NAME

Finanzierungstyp

### KAT_VEHICLE

Katalysator? vermutlich nicht relevant

### FUEL_TYPE

Nr. des FUEL_TYPE_NAME

### FUEL_TYPE_NAME

Treibstoffart

### DRIVE_TYPE

Nr. DRIVE_TYPE_NAME

### DRIVE_TYPE_NAME

Antriebsart (Vorderrad, Hinterrad, Allrad)

### VEHICLE_MODEL_ID

Nr. des VEHICLE_MODEL_ID_NAME

### VEHICLE_MODEL_ID_NAME

Modellbezeichnung

### COMMISSION_TYPE

Nr. des COMMISSION_TYPE_NAME

### COMMISSION_TYPE_NAME

Gebrauchtwagen/Neuwagen/Dienstwagen etc.

### DEMONSTRATION_STATUS

-

### PURCHASE_DATE

Zeitpunkt des Ankaufs

### PURCHASE_BOOKING_DATE

Zeitpunkt, wann der Ankauf verbucht wurde

### PURCHASE_MILAGE

Kilometerstand zu PURCHASE_DATE

### PURCHASE_OPERATION_HOURS

Irrelevant

### PRICE_LIST

Irrelevant

### DAY_OF_REGISTRATION

Irrelevant

### AT_LOCATION_SINCE

Zeitpunkt, seit dem das Auto am Standort ist (allerdings kein Date, anderes Speicherformat)

### LAID_UP_TIME

Zeitdauer, die das Auto vom Ankauf bis zum Verkauf beim Händler verbracht hat (Standzeit)

### SOLD_CUSTOMER_ID

Irrelevant

### SOLD_INVOICE_COSTUMER_ID

Irrelevant

### MILAGE_SALE

Gleich wie MILAGE_SALES

### OPERATION_HOURS_SALE

Irrelevant

### SOLD_INVOICE_COSTUMER_ID2

Gleich wie SOLD_INVOICE_COSTUMER_ID

### CUSTOMER_TYPE

Käuferart

### CUSTOMER_GROUP

ID des CUSTOMER_GROUP_NAME

### CUSTOMER_GROUP_NAME

Käufergruppe

### CUSTOMER_FEATURE

ID des CUSTOMER_FEATURE_NAME

### CUSTOMER_FEATURE_NAME

Käufereigenschaft ???? Also ist ein Grossabnehmer eine Eigenschaft?

### SALE_CUSTOMER_ID2

Gleich wie SALE_CUSTOMER_ID

### CUSTOMER_SALE_GROUP

ID des CUSTOMER_SALE_GROUP_NAME

### CUSTOMER_SALE_GROUP_NAME

-

### CUSTOMER_SALE_GROUP2

Gleich wie CUSTOMER_SALE_GROUP

### CUSTOMER_SALE_GROUP2_NAME

Gleich wie CUSTOMER_SALE_GROUP_NAME

### SCALED_CURRENT_VALUE

### SCALED_INVENTURAL_VALUE

### SCALED_REPORT_VALUE

### SCALED_VALUATION_PRICE

### SCALED_GUIDE_PRICE

### SCALED_TOTAL_SALES_PRICE_BASIS

### SCALED_TOTAL_SALE_PRICE

# Columns of interest

## CUSTOMER_TYPE

- Käuferart
- Kategorie

## RPAKREP_VEHICLE_HKEY

- Unique ID des Fahrzeugs

## COMPANY

- ID?
- Kategorie

## OFFICE

- ID einer spezifischen Niederlassung von Emil Frey
- Kategorie

## MANUFACTURER_SHORT

- Automarke
- Kategorie

## VEHICLE_GROUP

- Fahrzeugmodellgruppe
- Kategorie

## MILEAGE

- Laufleistung
- Numerisch

## COLOR

- Farbe
- Kategorie?

## UPHOLSTERY

- ID der Polsterung
- Kategorie

## ENGINE_TYPE

- Typ des Motors
- Kategorie

## TRANSMISSION_TYPE

- Getriebe
- Kategorie

## TRANSMISSION_NAME

- Art des Getriebes (Automatik, Handschalter, etc.)
- Kategorie

## NUMBER_DOORS

- Anzahl der Türen
- Numerisch

## NUMBER_SEATS

- Anzahl der Sitzplätze
- Numerisch

## CURB_WEIGHT

- Leergewicht
- Numerisch

## YEAR_CONSTRUCTION

- Baujahr
- Numerisch

## NUMBER_ENGINE_CYLINDER

- Anzahl der Zylinder
- Numerisch

## ACCIDENT_VEHICLE

- Unfallfahrzeug Ja/Nein
- boolean (True/False)

## HORSEPOWER

- Leistung in PS
- Numerisch

## CCM

- Hubraum in ccm
- Numerisch

## NUMBER_OWNERS

- Anzahl der Vorbesitzer
- Numerisch

## FINANCING_TYPE_NAME

- Art der Finanzierung
- Kategorie

## FUEL_TYPE_NAME

- Kraftstofftyp
- Kategorie

## DRIVE_TYPE_NAME

- Antriebsart (Vorderrad, Hinterrad, Allrad, etc.)
- Kategorie

## VEHICLE_MODEL_ID_NAME

- Fahrzeugkategorie (Geländewage, Limousine, etc.)
- Kategorie

## COMMISSION_TYPE_NAME

- Gebrauchtwagen/Neuwagen/Dienstwagen etc.
- Kategorie

## PURCHASE_DATE

- Ankaufdatum
- Numerisch

## LAID_UP_TIME

- Targetvalue
- Zeitdauer von An- bis Verkauf
- Numerisch

## CUSTOMER_SALE_GROUP2_NAME

- Art des Kunden (Endverbraucher, Interne Kunden, etc.)
- Kategorie

## SCALED_CURRENT_VALUE

- ???
- Numerisch

## SCALED_INVENTURAL_VALUE

- ???
- Numerisch

## SCALED_REPORT_VALUE

- ???
- Numerisch

## SCALED_VALUATION_PRICE

- ???
- Numerisch

## SCALED_GUIDE_PRICE

- ???
- Numerisch

## SCALED_TOTAL_SALES_PRICE_BASIS

- ???
- Numerisch

## SCALED_TOTAL_SALE_PRICE

- ???
- Numerisch

## SCALED_TOTAL_SALES_PRICE_DIFF

- ???
- Numerisch
