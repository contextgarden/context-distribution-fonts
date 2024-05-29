Version 2.35 added math tables to non math fonts which makes little sense and can only confuse matters. We didn't 
check the quality but in ConTeXt make sure to wipe the math related data from these fonts when we load them. Let 
us know if you run into issues. We keep the additional characters because in mono spaced usage they make sense. In 
ConTeXt one should not rely on math glyphs being present in text fonts!
