---
layout: post
author: bross
categories: [ code ]
image: assets/images/code.jpeg
description: "My review of Inception movie. Acting, plot and something else in this short description."
title: 'Some coding stuff'
---

Leverage agile ==frameworks to provide a robust synopsis== for high level overviews. Iterative approaches to corporate strategy foster collaborative thinking to further the overall value proposition. Organically grow the holistic world view of disruptive innovation via workplace diversity and empowerment.

---

Some code examples

```jsx
import React from 'react'
import { PhotoStory, VideoStory } from './stories'

const components = {
    photo: PhotoStory,
    video: VideoStory,
}

function Story(props) {
    // Correct! JSX type can be a capitalized variable.
    const SpecificStory = components[props.storyType]
    return <SpecificStory story={props.story} />
}
```

```info pro tip
Some admonitions
```

```warn wait up
Some admonitions
```

```error ohnoes
Some admonitions
```

And [^1] more including some [:ABBR](Abbreviation) syntax

```jsx
const Button = (props) => {
    const { kind, ...other } = props
    const className = kind === 'primary' ? 'PrimaryButton' : 'SecondaryButton'
    return <button className={className} {...other} />
}

const App = () => {
    return (
        <div>
            <Button kind='primary' onClick={() => console.log('clicked!')}>
                Hello World!
            </Button>
        </div>
    )
}
```

Remember that `false`, `null`, `undefined`, and `true` are not rendered in JSX.

:::warning Wait
Hold up
:::

![Vimeo link](https://vimeo.com/12739443)

![If programming was anime](https://www.youtube.com/watch?v=pKO9UjSeLew)

```tip Top tip
Hey
```

Don't forget to press <kbd>Ctrl</kbd><kbd>s</kbd> every 5 seconds.

Bring to the table win-win survival strategies to ensure proactive domination. At the end of the day, going forward, a new normal that has evolved from generation X is on the runway heading towards a streamlined cloud solution. User generated content in real-time will have multiple touchpoints for offshoring.

Capitalize on low hanging fruit to identify a ballpark value added activity to beta test. Override the digital divide with additional clickthroughs from DevOps. Nanotechnology immersion along the information highway will close the loop on focusing solely on the bottom line.

[^1]: Footnote about 'some'
