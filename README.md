# react-native-umtb-calendar-ui

Umtb-calendar

## Installation

```sh
npm install react-native-umtb-calendar-ui
```

## Usage

```js
import DateTimePicker from 'react-native-umtb-calendar-ui';

// ...

      <DateTimePicker
        mode="single"
        date={date}
        locale="he"
        selectedItemColor="#FF6600"
        dayContainerStyle={{
          borderRadius: 50,
        }}
        onChange={(params: any) => setDate(params.date)}
        // buttonPrevIcon={
        //   <UmtbDynamicArrowIcon height={30} width={12} direction="right" />
        // }

        // buttonNextIcon={<UmtbDynamicArrowIcon height={30} width={12} />}
        headerTextStyle={{
          lineHeight: 22,
        }}
        todayTextStyle={{
          lineHeight: 22,
          color: 'red',
        }}
        calendarTextStyle={{
          lineHeight: 22,
        }}
        weekDaysTextStyle={{
          lineHeight: 22,
        }}
        selectedTextStyle={{
          lineHeight: 22,
        }}
        timePickerTextStyle={{
          lineHeight: 22,
        }}
        displayFullDays
        // customHeader={({ monthSelector, yearSelector }) => (
        //   <CustomHeader
        //     monthSelector={monthSelector}
        //     yearSelector={yearSelector}
        //   />
        // )}
        weekDaysContainerStyle={{ borderBottomWidth: 0 }}
      />
```

how to install locally with `npm pack` after cloning the repo :
Inside the repository folder, run:

`npm pack`
If successful, this command will generate a .tgz (tarball) file. The filename will follow the pattern:

`<package-name>-<version>.tgz`
For example:
`react-native-umtb-calendar-ui-0.1.0.tgz`

and in your main project install it by running:
`npm install /path/to/repo-name/react-native-umtb-calendar-ui-0.1.0.tgz`

good luck :)

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
