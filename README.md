import xml.etree.ElementTree as ET

# Create the root element
root = ET.Element('playlist')
root.set('version', '1')
root.set('xmlns', 'http://xspf.org/ns/0/')

# Create the title element
title = ET.SubElement(root, 'title')
title.text = 'Top 10 Christian Songs'

# Create the creator element
creator = ET.SubElement(root, 'creator')
creator.text = 'John Doe'

# Create the tracklist element
tracklist = ET.SubElement(root, 'trackList')

# Create the first track
track1 = ET.SubElement(tracklist, 'track')
location1 = ET.SubElement(track1, 'location')
location1.text = 'https://www.youtube.com/watch?v=Zp6aygmvzM4'
title1 = ET.SubElement(track1, 'title')
title1.text = 'Way Maker - Leeland'

# Create the second track
track2 = ET.SubElement(tracklist, 'track')
location2 = ET.SubElement(track2, 'location')
location2.text = 'https://www.youtube.com/watch?v=RfJMSRJLayQ'
title2 = ET.SubElement(track2, 'title')
title2.text = 'Good Good Father - Chris Tomlin'

# Create the third track
track3 = ET.SubElement(tracklist, 'track')
location3 = ET.SubElement(track3, 'location')
location3.text = 'https://www.youtube.com/watch?v=_Yx8oBxV1mg'
title3 = ET.SubElement(track3, 'title')
title3.text = 'Reckless Love - Cory Asbury'

# Create the fourth track
track4 = ET.SubElement(tracklist, 'track')
location4 = ET.SubElement(track4, 'location')
location4.text = 'https://www.youtube.com/watch?v=0B_lnQIITxU'
title4 = ET.SubElement(track4, 'title')
title4.text = 'What A Beautiful Name - Hillsong Worship'

# Create the fifth track
track5 = ET.SubElement(tracklist, 'track')
location5 = ET.SubElement(track5, 'location')
location5.text = 'https://www.youtube.com/watch?v=sb9i0X0_-2Q'
title5 = ET.SubElement(track5, 'title')
title5.text = 'Oceans (Where Feet May Fail) - Hillsong United'

# Create the sixth track
track6 = ET.SubElement(tracklist, 'track')
location6 = ET.SubElement(track6, 'location')
location6.text = 'https://www.youtube.com/watch?v=3ztM_-W_FMs'
title6 = ET.SubElement(track6, 'title')
title6.text = 'Who You Say I Am - Hillsong Worship'

# Create the seventh track
track7 = ET.SubElement(tracklist, 'track')
location7 = ET.SubElement(track7, 'location')
location7.text = 'https://www.youtube.com/watch?v=lLxgtKIOZPE'
title7 = ET.SubElement(track7, 'title')
title7.text = 'Lord I Need You - Matt Maher'

# Create the eighth track
track8 = ET.SubElement(tracklist, 'track')
location8 = ET.SubElement(track8, 'location')
location8.text = 'https://www.youtube.com/watch?v=GzfPHnoT0-0'
title8 = ET.SubElement(track8, 'title')
title8.text = 'This Is Amazing Grace - Phil Wickham'

# Create the ninth track
track9 = ET.SubElement(tracklist, 'track')
location9 = ET.SubElement(track9, 'location')
location9


