# Mobile Crash Course
Crash course for engineers in Wix to start working on the mobile stack. Split into 5 days.

### [`Before:` Preliminaries](0-preliminaries.md)
Before starting the crash course, you should familiarize yourself with some basic concepts. Feel free to skip the parts you already know.

### [`Day 1:`Introduction to React Native](1-introduction-to-react-native.md)
This is the first official day of the crash course. We will start with introduction of the React Native framework and it's internals and later dive into different derivations of Flux design pattern. 



### [`Day 2:` TDD](2-tdd.md)
We will start from a talk about navigation solutions in React Native and continue some hardcore coding in TDD. It's not easy but once you nail a TDD workflow, the rewards are significant.



### [`Day 3:` Scaling & Deployment](3-scaling-and-deployment.md)
After understanding Wix OneApp's multi-module architecture and understand our the delivery process, we'll experiment with UI automation testing (E2E) and try to test our demo application with detox.



### [`Day 4:` Performance & Monitoring](4-performance-and-monitoring.md)
After understanding Wix OneApp's multi-module architecture and exploring our delivery process, we'll experiment with UI automation testing (E2E) and try to test our demo application with detox.


### [`Day 5:` More fun](5-more-fun.md)
On the last day we will take a look on the future of our mobile products in Wix and later we will try to improve our TDD skills by performing a TDD Kata.


### [`After:` Further Reading](https://github.com/wix/mobile-engineering-library)
We've just covered the tip of the iceberg. You probably have many open questions and things you'd like to understand in more depth. You can continue reading about what we think is important in our [mobile engineering library](https://github.com/wix/mobile-engineering-library).


## Full schedule
<p>&nbsp;</p>
<table style="width: 819px;">
<tbody>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;">
<p><strong>Day #</strong></p>
</td>
<td style="width: 125px; text-align: center;">
<p><strong>Time</strong></p>
</td>
<td style="width: 446px; text-align: center;">
<p><strong>Topic</strong></p>
</td>
<td style="width: 162px; text-align: center;">
<p><strong>Talk by</strong></p>
</td>
</tr>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;" rowspan="8">
<p><span style="font-weight: 400;">Day 1</span></p>
</td>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:00 - 10:30</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Introduction</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Lev.V</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:40-12:00</span></p>
</td>
<td style="width: 446px;">
<p class="p1"><span class="s1">Talk: ReactNative architecture - part 1</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Tal.K</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">12:00-12:40</span></p>
</td>
<td style="width: 446px;">&nbsp;<span class="s1">Workshop: Init a React Native project</span></td>
<td style="width: 162px;">&nbsp;<em>Lev.V + Nir.Yo</em></td>
</tr>
<tr>
<td style="width: 733px;" colspan="3">
<p><span style="font-weight: 400;">&nbsp;Lunch Break&nbsp;</span></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">13:50-15:30</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: ReactNative architecture - part 2</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Tal.K</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">15:40-16:15</span></p>
</td>
<td style="width: 446px;">
<p class="p1"><span class="s1">Talk: Flux Design Pattern &amp; Redux</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Yedidya</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">16:20-17:00</span></p>
</td>
<td style="width: 446px;">
<p class="p1"><span class="s1">Talk: Intreduction to RemX </span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Nir</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">17:00-19:00</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Workshop: Remx</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Nir + &nbsp;Yedidya</span></em></p>
</td>
</tr>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;" rowspan="5">
<p><span style="font-weight: 400;">Day 2</span></p>
</td>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:00 - 10:40</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Navigation - Idea, Pains &amp; Roadmap</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">(Guy.C-?) &amp; Ran.G &amp; Daniel</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:50 - 12:00</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Testing Redux</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Yedidya.K</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">12:00 - 12:55</span></p>
</td>
<td style="width: 446px;">&nbsp;Talk: TDD with Remx</td>
<td style="width: 162px;">&nbsp;<em>Daniel.Z</em></td>
</tr>
<tr>
<td style="width: 733px;" colspan="3">
<p>&nbsp;<span style="font-weight: 400;">Lunch Break</span></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">14:00 - 18:00</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Workshop: TDD Rewrite + using Navigation </span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Elad &amp; </span></em><em><span style="font-weight: 400;">Daniel.Z</span></em></p>
</td>
</tr>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;" rowspan="7">
<p><span style="font-weight: 400;">Day 3</span></p>
</td>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:00 - 10:55</span></p>
</td>
<td style="width: 446px;">
<p>Talk: Multi Module Architecture</p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Omri.B</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p>11:00 - 11:55</p>
</td>
<td style="width: 446px;">&nbsp;Talk: The Mighty UI Lib</td>
<td style="width: 162px;"><em>Eitan.S</em>&nbsp;</td>
</tr>
<tr>
<td style="width: 733px;" colspan="3">
<p><span style="font-weight: 400;">Lunch Break</span>&nbsp;</p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">13:00 - 13:30</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Frontend &amp; Backend Servers</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">TBD</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">13:30 - 14:55</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: CI, Build &amp; Distribution</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Sergey.L</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">15:00 - 15:55</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Detox and UI Automation Tests</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Rotem + Ran</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">16:00 - 18:00</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Workshop: Detoxify Your Project</span></p>
</td>
<td style="width: 162px;">
<p><em>Rotem + Ran</em></p>
</td>
</tr>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;" rowspan="5">
<p><span style="font-weight: 400;">Day 4</span></p>
</td>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:00-11:55</span></p>
</td>
<td style="width: 446px;">
<p>Performance &amp; Dev tools</p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Lev + Nir</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">12:00 - 12:55</span></p>
</td>
<td style="width: 446px;">&nbsp;Talk: Experiments, BI &amp; Monitoring</td>
<td style="width: 162px;">&nbsp;<em>Noam</em></td>
</tr>
<tr>
<td style="width: 733px;" colspan="3">
<p><span style="font-weight: 400;">Lunch Break</span></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">14:00 - 14:55 </span></p>
</td>
<td style="width: 446px;">
<p>Talk: Code Sharing</p>
</td>
<td style="width: 162px;">
<p><em>Aaron</em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">15:00-18:00</span></p>
</td>
<td style="width: 446px;">
<p>Workshop: Integrate with OneApp</p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Lev.V+Artal</span></em></p>
</td>
</tr>
<tr>
<td style="background-color: #ffffff; width: 70px; text-align: center;" rowspan="5">
<p><span style="font-weight: 400;">Day 5</span></p>
</td>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">10:00 - 11:00</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Discussion: Meet the Guild (with the guild)</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Guildday</span></em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">11:00 - 11:50</span></p>
</td>
<td style="width: 446px;">
<p><span style="font-weight: 400;">Talk: Mobile Product What's New</span></p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">Dror.B</span></em></p>
</td>
</tr>
<tr>
<td style="width: 733px;" colspan="3">
<p><span style="font-weight: 400;">Lunch Break</span></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">13:00-17:00</span></p>
</td>
<td style="width: 446px;">
<p>Workshop: TDD Kata</p>
</td>
<td style="width: 162px;">
<p><em>Daniel.Z</em></p>
</td>
</tr>
<tr>
<td style="width: 125px; text-align: center;">
<p><span style="font-weight: 400;">17:00-19:00</span></p>
</td>
<td style="width: 446px;">
<p>Discussion: Summary, Feedback &amp; Beer</p>
</td>
<td style="width: 162px;">
<p><em><span style="font-weight: 400;">All invited</span></em></p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
