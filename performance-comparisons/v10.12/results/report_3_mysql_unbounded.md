### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | avg | 1ms | 1.258s | 1.257s | 120305.62
| EmojiStore.GetMultipleByName | avg | 4ms | 109ms | 105ms | 2632.45
| RoleStore.GetByNames | avg | 20ms | 179ms | 159ms | 808.65
| RoleStore.ChannelHigherScopedPermissions | avg | 18ms | 154ms | 136ms | 773.58
| ChannelStore.GetMembers | avg | 21ms | 143ms | 122ms | 574.59
| JobStore.GetAllByTypePage | avg | 67ms | 301ms | 234ms | 350.43
| TeamStore.AnalyticsTeamCount | avg | 56ms | 119ms | 63ms | 111.78
| PostPersistentNotificationStore.DeleteExpired | avg | 4ms | 7ms | 3ms | 80.49
| CommandWebhookStore.Cleanup | avg | 13ms | 20ms | 7ms | 55.65
| ThreadStore.MarkAllAsReadByTeam | avg | 14ms | 20ms | 6ms | 42.55
| UserAccessTokenStore.GetByToken | avg | 32ms | 45ms | 13ms | 40.92
| SessionStore.Remove | avg | 6ms | 8ms | 2ms | 35.56
| PostPersistentNotificationStore.Get | avg | 6ms | 8ms | 2ms | 33.80
| ChannelBookmarkStore.UpdateSortOrder | avg | 83ms | 106ms | 23ms | 27.69
| PostStore.AnalyticsPostCount | avg | 1.007s | 1.231s | 224ms | 22.23
| StatusStore.UpdateExpiredDNDStatuses | avg | 22ms | 26ms | 4ms | 18.58
| ChannelStore.UpdateSidebarCategories | avg | 52ms | 60ms | 8ms | 15.33
| PropertyValueStore.SearchPropertyValues | avg | 60ms | 69ms | 9ms | 15.04
| UserStore.AnalyticsActiveCount | avg | 550ms | 631ms | 81ms | 14.73
| ChannelStore.CreateDirectChannel | avg | 184ms | 206ms | 22ms | 11.93
| PostStore.GetPostReminders | avg | 17ms | 19ms | 2ms | 11.82
| PostStore.Update | avg | 28ms | 31ms | 3ms | 10.81
| PostPriorityStore.GetForPost | avg | 47ms | 52ms | 5ms | 10.57
| UserStore.GetMany | avg | 45ms | 49ms | 4ms | 8.94
| ChannelStore.GetMemberCount | avg | 246ms | 257ms | 11ms | 4.46
| TeamStore.Get | avg | 48ms | 50ms | 2ms | 4.16
| PostPriorityStore.GetForPosts | avg | 76ms | 79ms | 3ms | 3.94
| LinkMetadataStore.Get | avg | 51ms | 53ms | 2ms | 3.93
| StatusStore.GetByIds | avg | 77ms | 80ms | 3ms | 3.89
| ChannelStore.GetPinnedPostCount | avg | 56ms | 58ms | 2ms | 3.56
| PostStore.GetPostsByThread | avg | 57ms | 59ms | 2ms | 3.49
| ThreadStore.GetThreadUnreadReplyCount | avg | 61ms | 63ms | 2ms | 3.29
| JobStore.GetAllByStatus | avg | 62ms | 64ms | 2ms | 3.23
| ChannelBookmarkStore.Save | avg | 62ms | 64ms | 2ms | 3.21
| ChannelStore.SaveMember | avg | 188ms | 194ms | 6ms | 3.19
| ChannelStore.GetGuestCount | avg | 66ms | 68ms | 2ms | 3.04
| ChannelStore.GetMemberForPost | avg | 69ms | 71ms | 2ms | 2.90
| DraftStore.Get | avg | 69ms | 71ms | 2ms | 2.90
| PostAcknowledgementStore.GetForPosts | avg | 73ms | 75ms | 2ms | 2.74
| ThreadStore.GetThreadForUser | avg | 74ms | 76ms | 2ms | 2.71
| PostStore.GetPostsSince | avg | 77ms | 79ms | 2ms | 2.58
| ChannelStore.Get | avg | 110ms | 112ms | 2ms | 1.82
| TeamStore.SaveMember | avg | 128ms | 130ms | 2ms | 1.56
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ComplianceStore.MessageExport | p99 | 5ms | 4.925s | 4.92s | 99370.08
| EmojiStore.GetMultipleByName | p99 | 23ms | 476ms | 453ms | 1991.21
| RoleStore.ChannelHigherScopedPermissions | p99 | 132ms | 990ms | 858ms | 652.47
| TeamStore.AnalyticsTeamCount | p99 | 100ms | 488ms | 388ms | 389.95
| RoleStore.GetByNames | p99 | 222ms | 952ms | 730ms | 328.18
| ChannelStore.GetMembers | p99 | 232ms | 935ms | 703ms | 302.98
| PostPersistentNotificationStore.DeleteExpired | p99 | 40ms | 138ms | 98ms | 242.73
| SessionStore.Remove | p99 | 32ms | 84ms | 52ms | 160.00
| UserStore.AnalyticsActiveCount | p99 | 990ms | 2.35s | 1.36s | 137.37
| ChannelBookmarkStore.Save | p99 | 795ms | 1.675s | 880ms | 110.69
| CommandWebhookStore.Cleanup | p99 | 49ms | 97ms | 48ms | 97.96
| ChannelBookmarkStore.UpdateSortOrder | p99 | 487ms | 960ms | 473ms | 97.03
| PostStore.Delete | p99 | 459ms | 805ms | 346ms | 75.42
| PostStore.SetPostReminder | p99 | 225ms | 380ms | 155ms | 68.81
| ClusterDiscoveryStore.SetLastPingAt | p99 | 97ms | 163ms | 66ms | 67.99
| PostPersistentNotificationStore.Get | p99 | 85ms | 138ms | 53ms | 62.23
| JobStore.GetCountByStatusAndType | p99 | 489ms | 685ms | 196ms | 40.04
| StatusStore.SaveOrUpdateMany | p99 | 122ms | 158ms | 36ms | 29.51
| JobStore.GetNewestJobByStatusesAndType | p99 | 480ms | 620ms | 140ms | 29.17
| PostPriorityStore.GetForPost | p99 | 678ms | 844ms | 166ms | 24.50
| PostStore.GetPostReminders | p99 | 180ms | 216ms | 36ms | 20.06
| ScheduledPostStore.CreateScheduledPost | p99 | 69ms | 82ms | 13ms | 18.91
| UserAccessTokenStore.GetByToken | p99 | 710ms | 840ms | 130ms | 18.31
| PostStore.Update | p99 | 191ms | 225ms | 34ms | 17.83
| JobStore.UpdateStatusOptimistically | p99 | 186ms | 213ms | 27ms | 14.52
| ChannelStore.GetMemberCount | p99 | 1.094s | 1.239s | 145ms | 13.26
| ThreadStore.MarkAsRead | p99 | 77ms | 86ms | 9ms | 11.63
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 200ms | 221ms | 21ms | 10.47
| StatusStore.UpdateExpiredDNDStatuses | p99 | 217ms | 239ms | 22ms | 10.14
| PropertyValueStore.SearchPropertyValues | p99 | 803ms | 884ms | 81ms | 10.08
| DraftStore.Delete | p99 | 86ms | 94ms | 8ms | 9.30
| JobStore.GetAllByTypePage | p99 | 898ms | 980ms | 82ms | 9.13
| UserStore.Get | p99 | 501ms | 544ms | 43ms | 8.59
| UserTermsOfServiceStore.GetByUser | p99 | 546ms | 592ms | 46ms | 8.42
| ChannelStore.GetChannelUnread | p99 | 521ms | 556ms | 35ms | 6.72
| ChannelStore.GetPinnedPostCount | p99 | 774ms | 824ms | 50ms | 6.46
| TeamStore.GetMember | p99 | 249ms | 265ms | 16ms | 6.41
| PostPriorityStore.GetForPosts | p99 | 1.344s | 1.427s | 83ms | 6.18
| SessionStore.GetSessionsExpired | p99 | 450ms | 476ms | 26ms | 5.78
| UserStore.UpdateUpdateAt | p99 | 71ms | 75ms | 4ms | 5.61
| ChannelStore.UpdateLastViewedAt | p99 | 144ms | 152ms | 8ms | 5.55
| SessionStore.UpdateLastActivityAt | p99 | 73ms | 77ms | 4ms | 5.47
| PostAcknowledgementStore.GetForPost | p99 | 651ms | 684ms | 33ms | 5.07
| PostAcknowledgementStore.GetForPosts | p99 | 1.28s | 1.343s | 63ms | 4.92
| ChannelStore.SearchGroupChannels | p99 | 812ms | 851ms | 39ms | 4.80
| StatusStore.UpdateLastActivityAt | p99 | 84ms | 88ms | 4ms | 4.78
| TeamStore.SaveMember | p99 | 731ms | 765ms | 34ms | 4.65
| UserStore.GetByUsername | p99 | 682ms | 713ms | 31ms | 4.54
| ThreadStore.MarkAllAsReadByChannels | p99 | 88ms | 92ms | 4ms | 4.53
| UserStore.Save | p99 | 289ms | 302ms | 13ms | 4.50
| ThreadStore.GetThreadUnreadReplyCount | p99 | 822ms | 857ms | 35ms | 4.26
| ChannelStore.GetByName | p99 | 556ms | 577ms | 21ms | 3.78
| PropertyFieldStore.SearchPropertyFields | p99 | 432ms | 447ms | 15ms | 3.47
| ThreadStore.UpdateMembership | p99 | 88ms | 91ms | 3ms | 3.41
| ChannelStore.GetMembersForUser | p99 | 771ms | 796ms | 25ms | 3.24
| PostStore.GetPostsAfter | p99 | 754ms | 778ms | 24ms | 3.18
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 678ms | 699ms | 21ms | 3.10
| SystemStore.GetByName | p99 | 66ms | 68ms | 2ms | 3.04
| StatusStore.GetByIds | p99 | 898ms | 925ms | 27ms | 3.01
| PostPersistentNotificationStore.GetSingle | p99 | 818ms | 842ms | 24ms | 2.93
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 499ms | 513ms | 14ms | 2.80
| JobStore.GetAllByStatus | p99 | 805ms | 827ms | 22ms | 2.73
| PostStore.GetSingle | p99 | 743ms | 763ms | 20ms | 2.69
| EmojiStore.GetByName | p99 | 796ms | 817ms | 21ms | 2.64
| UserStore.GetProfileByIds | p99 | 610ms | 626ms | 16ms | 2.62
| LinkMetadataStore.Get | p99 | 751ms | 770ms | 19ms | 2.53
| ChannelStore.IncrementMentionCount | p99 | 80ms | 82ms | 2ms | 2.50
| UserStore.GetUnreadCount | p99 | 692ms | 709ms | 17ms | 2.46
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 645ms | 660ms | 15ms | 2.33
| ChannelStore.GetChannels | p99 | 799ms | 817ms | 18ms | 2.25
| ChannelStore.GetGuestCount | p99 | 803ms | 821ms | 18ms | 2.24
| DraftStore.Get | p99 | 854ms | 873ms | 19ms | 2.22
| ChannelStore.GetMemberForPost | p99 | 865ms | 884ms | 19ms | 2.20
| TeamStore.Get | p99 | 732ms | 748ms | 16ms | 2.19
| ChannelStore.CreateSidebarCategory | p99 | 470ms | 480ms | 10ms | 2.13
| ProductNoticesStore.View | p99 | 387ms | 395ms | 8ms | 2.07
| ChannelStore.GetFileCount | p99 | 443ms | 452ms | 9ms | 2.03
| PreferenceStore.Get | p99 | 698ms | 712ms | 14ms | 2.01
| ThreadStore.GetThreadsForUser | p99 | 820ms | 834ms | 14ms | 1.71
| PostStore.GetPostsSince | p99 | 824ms | 838ms | 14ms | 1.70
| FileInfoStore.Get | p99 | 472ms | 478ms | 6ms | 1.27
| ChannelStore.IsReadOnlyChannel | p99 | 459ms | 464ms | 5ms | 1.09
| PostStore.GetEtag | p99 | 739ms | 747ms | 8ms | 1.08
| ChannelStore.SaveMember | p99 | 2.264s | 2.288s | 24ms | 1.06
| ThreadStore.MaintainMembership | p99 | 189ms | 191ms | 2ms | 1.06
| TeamStore.GetTeamsByUserId | p99 | 495ms | 500ms | 5ms | 1.01
| GroupStore.GetGroups | p99 | 797ms | 805ms | 8ms | 1.00
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| RetentionPolicyStore.GetCount | avg | 48ms | 0s | -48ms | -100.82
| ChannelStore.GetMemberCountsByGroup | avg | 16ms | 0s | -16ms | -100.80
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | avg | 4ms | 0s | -4ms | -100.73
| PostPersistentNotificationStore.UpdateLastActivity | avg | 22ms | 0s | -22ms | -100.34
| RetentionPolicyStore.GetAll | avg | 55ms | 0s | -55ms | -100.33
| ChannelStore.GetChannelsByIds | avg | 85ms | 0s | -85ms | -99.94
| SchemeStore.GetAllPage | avg | 73ms | 1ms | -72ms | -99.30
| PostStore.GetPostsByIds | avg | 43ms | 0s | -43ms | -99.14
| TeamStore.GetMany | avg | 29ms | 0s | -29ms | -98.73
| ScheduledPostStore.Get | avg | 9ms | 0s | -9ms | -96.17
| DesktopTokensStore.DeleteOlderThan | avg | 14ms | 2ms | -12ms | -87.67
| LicenseStore.GetAll | avg | 71ms | 13ms | -58ms | -81.59
| ChannelBookmarkStore.Delete | avg | 48ms | 14ms | -34ms | -70.62
| UserStore.AnalyticsGetInactiveUsersCount | avg | 340ms | 103ms | -237ms | -69.65
| UserStore.GetProfilesNotInChannel | avg | 90ms | 30ms | -60ms | -67.01
| TokenStore.Cleanup | avg | 25ms | 10ms | -15ms | -61.00
| ScheduledPostStore.GetPendingScheduledPosts | avg | 124ms | 61ms | -63ms | -50.84
| BotStore.Get | avg | 112ms | 56ms | -56ms | -50.06
| ChannelBookmarkStore.Get | avg | 153ms | 78ms | -75ms | -48.94
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 9ms | 5ms | -4ms | -47.03
| UserStore.GetProfilesInChannel | avg | 88ms | 52ms | -36ms | -41.04
| ChannelStore.AnalyticsCountAll | avg | 587ms | 357ms | -230ms | -39.18
| PostStore.Delete | avg | 77ms | 49ms | -28ms | -36.14
| JobStore.GetCountByStatusAndType | avg | 62ms | 40ms | -22ms | -35.54
| PluginStore.List | avg | 73ms | 51ms | -22ms | -30.17
| SessionStore.GetSessionsExpired | avg | 54ms | 39ms | -15ms | -27.57
| ChannelStore.GetTeamChannels | avg | 120ms | 89ms | -31ms | -25.74
| TeamStore.GetActiveMemberCount | avg | 308ms | 230ms | -78ms | -25.33
| JobStore.Save | avg | 8ms | 6ms | -2ms | -24.24
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 80ms | 61ms | -19ms | -23.62
| TeamStore.GetTotalMemberCount | avg | 244ms | 190ms | -54ms | -22.13
| PostStore.AnalyticsPostCountByTeam | avg | 1.627s | 1.275s | -352ms | -21.64
| JobStore.GetNewestJobByStatusesAndType | avg | 50ms | 41ms | -9ms | -17.88
| ChannelStore.GetSidebarCategory | avg | 111ms | 93ms | -18ms | -16.21
| PostStore.SetPostReminder | avg | 25ms | 21ms | -4ms | -15.81
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 48ms | 41ms | -7ms | -14.59
| ChannelStore.GetPublicChannelsForTeam | avg | 86ms | 75ms | -11ms | -12.74
| FileInfoStore.GetForPost | avg | 69ms | 61ms | -8ms | -11.60
| DraftStore.GetDraftsForUser | avg | 71ms | 63ms | -8ms | -11.22
| PostStore.SearchPostsForUser | avg | 118ms | 105ms | -13ms | -11.00
| ChannelStore.GetChannelsByUser | avg | 35ms | 32ms | -3ms | -8.56
| ChannelStore.AutocompleteInTeamForSearch | avg | 303ms | 278ms | -25ms | -8.25
| UserStore.GetByUsername | avg | 52ms | 48ms | -4ms | -7.63
| ChannelStore.GetChannelUnread | avg | 43ms | 40ms | -3ms | -7.06
| PostStore.GetPostReminderMetadata | avg | 75ms | 70ms | -5ms | -6.64
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 66ms | 62ms | -4ms | -6.05
| ScheduledPostStore.GetScheduledPostsForUser | avg | 33ms | 31ms | -2ms | -6.02
| TeamStore.GetTeamsForUser | avg | 37ms | 35ms | -2ms | -5.45
| ChannelStore.Save | avg | 95ms | 90ms | -5ms | -5.29
| FileInfoStore.GetByIds | avg | 63ms | 61ms | -2ms | -3.19
| UserStore.AutocompleteUsersInChannel | avg | 400ms | 390ms | -10ms | -2.50
| UserStore.Search | avg | 182ms | 179ms | -3ms | -1.65
| ChannelStore.Autocomplete | avg | 1.526s | 1.505s | -21ms | -1.38
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.Get | p99 | 25ms | 0s | -25ms | -101.19
| EmojiStore.Search | p99 | 5ms | 0s | -5ms | -101.01
| SystemStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | p99 | 5ms | 0s | -5ms | -100.97
| RetentionPolicyStore.GetAll | p99 | 100ms | 0s | -100ms | -100.50
| RetentionPolicyStore.GetCount | p99 | 50ms | 0s | -50ms | -100.50
| ChannelStore.GetMemberCountsByGroup | p99 | 237ms | 0s | -237ms | -100.21
| PostStore.GetPostsByIds | p99 | 243ms | 0s | -243ms | -100.21
| TeamStore.GetMany | p99 | 241ms | 0s | -241ms | -100.00
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 235ms | 0s | -235ms | -100.00
| ChannelStore.GetChannelsByIds | p99 | 945ms | 0s | -945ms | -100.00
| SchemeStore.GetAllPage | p99 | 100ms | 5ms | -95ms | -95.48
| DesktopTokensStore.DeleteOlderThan | p99 | 25ms | 5ms | -20ms | -80.48
| TokenStore.Cleanup | p99 | 238ms | 48ms | -190ms | -79.83
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 1.795s | 472ms | -1.323s | -73.70
| BotStore.Get | p99 | 2.14s | 770ms | -1.37s | -64.02
| ChannelBookmarkStore.Delete | p99 | 234ms | 93ms | -141ms | -60.39
| ChannelBookmarkStore.Get | p99 | 2.005s | 825ms | -1.18s | -58.85
| TeamStore.GetActiveMemberCount | p99 | 1.96s | 945ms | -1.015s | -51.79
| UserStore.GetProfilesNotInChannel | p99 | 485ms | 234ms | -251ms | -51.74
| UserStore.AnalyticsGetInactiveUsersCount | p99 | 497ms | 246ms | -251ms | -50.45
| JobStore.Save | p99 | 79ms | 40ms | -39ms | -49.58
| TeamStore.GetTotalMemberCount | p99 | 940ms | 489ms | -451ms | -47.98
| PostStore.GetPostReminderMetadata | p99 | 1.517s | 845ms | -672ms | -44.28
| PreferenceStore.DeleteCategoryAndName | p99 | 83ms | 47ms | -36ms | -43.11
| UserStore.GetProfilesInChannel | p99 | 785ms | 479ms | -306ms | -38.98
| LinkMetadataStore.Save | p99 | 118ms | 76ms | -42ms | -35.59
| ChannelStore.GetSidebarCategory | p99 | 1.33s | 905ms | -425ms | -31.95
| PluginStore.List | p99 | 1.06s | 770ms | -290ms | -27.36
| JobStore.UpdateStatus | p99 | 93ms | 69ms | -24ms | -25.81
| FileInfoStore.SetContent | p99 | 176ms | 136ms | -40ms | -22.69
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 929ms | 742ms | -187ms | -20.12
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 88ms | 77ms | -11ms | -12.46
| DraftStore.GetDraftsForUser | p99 | 894ms | 788ms | -106ms | -11.86
| PostStore.SearchPostsForUser | p99 | 1.085s | 975ms | -110ms | -10.14
| UserStore.UpdateLastLogin | p99 | 64ms | 58ms | -6ms | -9.33
| ChannelStore.GetPublicChannelsForTeam | p99 | 853ms | 779ms | -74ms | -8.68
| FileInfoStore.AttachToPost | p99 | 95ms | 87ms | -8ms | -8.38
| ReactionStore.GetForPost | p99 | 805ms | 740ms | -65ms | -8.07
| ChannelStore.UpdateSidebarCategories | p99 | 479ms | 441ms | -38ms | -7.94
| StatusStore.Get | p99 | 699ms | 653ms | -46ms | -6.58
| FileInfoStore.GetByIds | p99 | 878ms | 827ms | -51ms | -5.81
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 470ms | 446ms | -24ms | -5.10
| UserStore.Update | p99 | 105ms | 100ms | -5ms | -4.75
| FileInfoStore.GetForPost | p99 | 917ms | 876ms | -41ms | -4.47
| PostStore.GetPosts | p99 | 435ms | 418ms | -17ms | -3.90
| ChannelStore.Save | p99 | 975ms | 937ms | -38ms | -3.90
| ThreadStore.GetTotalUnreadMentions | p99 | 583ms | 564ms | -19ms | -3.26
| LicenseStore.GetAll | p99 | 100ms | 97ms | -3ms | -3.02
| SessionStore.Save | p99 | 479ms | 465ms | -14ms | -2.93
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 893ms | 869ms | -24ms | -2.69
| ChannelStore.CreateInitialSidebarCategories | p99 | 233ms | 227ms | -6ms | -2.57
| ChannelStore.GetChannelsByUser | p99 | 474ms | 462ms | -12ms | -2.53
| SessionStore.Get | p99 | 586ms | 573ms | -13ms | -2.22
| TeamStore.GetTeamsForUser | p99 | 482ms | 472ms | -10ms | -2.07
| ChannelStore.AnalyticsCountAll | p99 | 995ms | 975ms | -20ms | -2.01
| FileInfoStore.Save | p99 | 100ms | 98ms | -2ms | -2.00
| ChannelStore.GetTeamChannels | p99 | 908ms | 890ms | -18ms | -1.98
| ChannelStore.GetMemberLastViewedAt | p99 | 461ms | 452ms | -9ms | -1.95
| ThreadStore.GetTeamsUnreadForUser | p99 | 841ms | 825ms | -16ms | -1.90
| SessionStore.GetLRUSessions | p99 | 480ms | 471ms | -9ms | -1.88
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 497ms | 488ms | -9ms | -1.81
| UserStore.GetForLogin | p99 | 476ms | 469ms | -7ms | -1.47
| UserStore.IsEmpty | p99 | 416ms | 410ms | -6ms | -1.44
| ThreadStore.GetTotalThreads | p99 | 493ms | 486ms | -7ms | -1.42
| UserStore.AutocompleteUsersInChannel | p99 | 2.051s | 2.022s | -29ms | -1.41
| ThreadStore.GetMembershipForUser | p99 | 817ms | 808ms | -9ms | -1.10
| GroupStore.GetByName | p99 | 470ms | 465ms | -5ms | -1.06
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | avg | 26ms | 152ms | 126ms | 489.54
| getJobsByType | avg | 67ms | 301ms | 234ms | 347.65
| createSchedulePost | avg | 13ms | 29ms | 16ms | 126.03
| logout | avg | 92ms | 188ms | 96ms | 104.60
| setPostReminder | avg | 178ms | 305ms | 127ms | 71.37
| updateReadStateAllThreadsByUser | avg | 14ms | 20ms | 6ms | 42.20
| createCategoryForTeamForUser | avg | 142ms | 190ms | 48ms | 33.91
| listCPAValues | avg | 63ms | 73ms | 10ms | 15.89
| getChannel | avg | 110ms | 125ms | 15ms | 13.66
| unfollowThreadByUser | avg | 143ms | 160ms | 17ms | 11.93
| createDirectChannel | avg | 626ms | 683ms | 57ms | 9.11
| patchPost | avg | 361ms | 389ms | 28ms | 7.76
| getChannelStats | avg | 32ms | 34ms | 2ms | 6.27
| getUsers | avg | 35ms | 37ms | 2ms | 5.79
| getUser | avg | 63ms | 66ms | 3ms | 4.74
| createChannelBookmark | avg | 99ms | 103ms | 4ms | 4.05
| updateReadStateThreadByUser | avg | 504ms | 524ms | 20ms | 3.97
| getPostsForChannel | avg | 541ms | 561ms | 20ms | 3.70
| viewChannel | avg | 171ms | 177ms | 6ms | 3.50
| searchGroupChannels | avg | 65ms | 67ms | 2ms | 3.07
| deleteDraft | avg | 70ms | 72ms | 2ms | 2.87
| addTeamMember | avg | 2.134s | 2.193s | 59ms | 2.76
| createGroupChannel | avg | 1.216s | 1.247s | 31ms | 2.55
| getPostThread | avg | 330ms | 337ms | 7ms | 2.12
| saveReaction | avg | 182ms | 185ms | 3ms | 1.65
| createPost | avg | 1.014s | 1.028s | 14ms | 1.38
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getChannelMembers | p99 | 232ms | 935ms | 703ms | 302.98
| getRolesByNames | p99 | 247ms | 935ms | 688ms | 278.54
| createChannelBookmark | p99 | 835ms | 1.855s | 1.02s | 122.16
| deleteChannelBookmark | p99 | 247ms | 493ms | 246ms | 99.58
| getAnalytics | p99 | 2.485s | 4.925s | 2.44s | 98.19
| getFilteredUsersStats | p99 | 497ms | 980ms | 483ms | 97.09
| updateChannelBookmarkSortOrder | p99 | 493ms | 970ms | 477ms | 96.69
| createCategoryForTeamForUser | p99 | 490ms | 960ms | 470ms | 95.92
| setPostReminder | p99 | 2.005s | 3.8s | 1.795s | 89.53
| logout | p99 | 1.45s | 2.185s | 735ms | 50.69
| getChannel | p99 | 1.259s | 1.887s | 628ms | 49.89
| getUsers | p99 | 498ms | 621ms | 123ms | 24.68
| createSchedulePost | p99 | 213ms | 247ms | 34ms | 16.00
| createGroupChannel | p99 | 7.931s | 8.925s | 994ms | 12.53
| createDirectChannel | p99 | 4.033s | 4.506s | 473ms | 11.73
| unfollowThreadByUser | p99 | 1.656s | 1.808s | 152ms | 9.18
| getJobsByType | p99 | 898ms | 980ms | 82ms | 9.13
| listCPAValues | p99 | 833ms | 906ms | 73ms | 8.77
| patchPost | p99 | 3.858s | 4.158s | 300ms | 7.78
| getUser | p99 | 856ms | 918ms | 62ms | 7.25
| createUser | p99 | 3.318s | 3.528s | 210ms | 6.33
| getTeamMember | p99 | 128ms | 136ms | 8ms | 6.24
| searchGroupChannels | p99 | 812ms | 851ms | 39ms | 4.80
| getChannelStats | p99 | 807ms | 840ms | 33ms | 4.09
| getChannelMembersForTeamForUser | p99 | 772ms | 796ms | 24ms | 3.11
| getChannelUnread | p99 | 620ms | 638ms | 18ms | 2.90
| getPostsForChannel | p99 | 8.842s | 9.091s | 249ms | 2.82
| listCPAFields | p99 | 456ms | 468ms | 12ms | 2.63
| getFileThumbnail | p99 | 745ms | 764ms | 19ms | 2.55
| getFilePreview | p99 | 686ms | 702ms | 16ms | 2.33
| deleteDraft | p99 | 855ms | 874ms | 19ms | 2.22
| viewChannel | p99 | 2.358s | 2.409s | 51ms | 2.16
| getChannelsForTeamForUser | p99 | 799ms | 816ms | 17ms | 2.13
| createPost | p99 | 8.289s | 8.421s | 132ms | 1.59
| saveReaction | p99 | 2.227s | 2.251s | 24ms | 1.08
| getTeamsForUser | p99 | 495ms | 500ms | 5ms | 1.01
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteScheduledPost | avg | 5ms | 0s | -5ms | -107.66
| channelMemberCountsByGroup | avg | 16ms | 0s | -16ms | -99.96
| getPrevTrialLicense | avg | 58ms | 18ms | -40ms | -68.75
| deletePost | avg | 291ms | 103ms | -188ms | -64.54
| getRolesByNames | avg | 117ms | 42ms | -75ms | -64.29
| updateChannelBookmark | avg | 454ms | 172ms | -282ms | -62.08
| createChannel | avg | 1.246s | 731ms | -515ms | -41.32
| getTeamStats | avg | 321ms | 244ms | -77ms | -24.01
| getFilteredUsersStats | avg | 368ms | 295ms | -73ms | -19.86
| getAnalytics | avg | 2.273s | 1.823s | -450ms | -19.80
| followThreadByUser | avg | 186ms | 153ms | -33ms | -17.72
| getPublicChannelsForTeam | avg | 87ms | 76ms | -11ms | -12.59
| updateCategoriesForTeamForUser | avg | 324ms | 285ms | -39ms | -12.03
| searchPostsInTeam | avg | 225ms | 198ms | -27ms | -11.98
| getDrafts | avg | 76ms | 67ms | -9ms | -11.84
| addChannelMember | avg | 1.105s | 1.006s | -99ms | -8.96
| autocompleteChannelsForTeamForSearch | avg | 303ms | 279ms | -24ms | -7.92
| getTeamScheduledPosts | avg | 67ms | 62ms | -5ms | -7.49
| uploadFileStream | avg | 553ms | 518ms | -35ms | -6.33
| getCategoriesForTeamForUser | avg | 67ms | 63ms | -4ms | -6.00
| removeUserCustomStatus | avg | 315ms | 297ms | -18ms | -5.71
| getChannelsForUser | avg | 35ms | 33ms | -2ms | -5.68
| getChannelMembersForUser | avg | 41ms | 39ms | -2ms | -4.94
| updateChannelBookmarkSortOrder | avg | 149ms | 142ms | -7ms | -4.68
| getProfileImage | avg | 87ms | 83ms | -4ms | -4.62
| deleteChannelBookmark | avg | 114ms | 109ms | -5ms | -4.37
| getChannelUnread | avg | 46ms | 44ms | -2ms | -4.37
| autocompleteUsers | avg | 347ms | 334ms | -13ms | -3.75
| getPreferences | avg | 55ms | 53ms | -2ms | -3.65
| getPostsForChannelAroundLastUnread | avg | 168ms | 163ms | -5ms | -2.97
| getTeamsUnreadForUser | avg | 74ms | 72ms | -2ms | -2.71
| login | avg | 193ms | 189ms | -4ms | -2.07
| searchAllChannels | avg | 1.528s | 1.507s | -21ms | -1.37
| searchUsers | avg | 183ms | 181ms | -2ms | -1.09
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| autocompleteEmojis | p99 | 5ms | 0s | -5ms | -101.01
| deleteScheduledPost | p99 | 5ms | 0s | -5ms | -100.97
| channelMemberCountsByGroup | p99 | 237ms | 0s | -237ms | -100.21
| updateChannelBookmark | p99 | 4.7s | 975ms | -3.725s | -79.26
| deletePost | p99 | 4.175s | 903ms | -3.272s | -78.37
| getTeamStats | p99 | 1.96s | 945ms | -1.015s | -51.79
| createChannel | p99 | 8.15s | 4.45s | -3.7s | -45.40
| updateCategoriesForTeamForUser | p99 | 3.538s | 2.358s | -1.18s | -33.36
| followThreadByUser | p99 | 1.96s | 1.615s | -345ms | -17.60
| addChannelMember | p99 | 9.23s | 7.667s | -1.563s | -16.93
| searchPostsInTeam | p99 | 3.052s | 2.605s | -447ms | -14.65
| getPublicChannelsForTeam | p99 | 853ms | 779ms | -74ms | -8.68
| getDrafts | p99 | 932ms | 855ms | -77ms | -8.26
| uploadFileStream | p99 | 2.16s | 2.002s | -158ms | -7.31
| getTeamScheduledPosts | p99 | 922ms | 861ms | -61ms | -6.62
| removeUserCustomStatus | p99 | 2.6s | 2.435s | -165ms | -6.35
| getPostThread | p99 | 3.745s | 3.603s | -142ms | -3.79
| getAllTeams | p99 | 586ms | 568ms | -18ms | -3.07
| getCategoriesForTeamForUser | p99 | 896ms | 874ms | -22ms | -2.46
| login | p99 | 2.042s | 1.993s | -49ms | -2.40
| getChannelsForUser | p99 | 474ms | 463ms | -11ms | -2.32
| getPrevTrialLicense | p99 | 100ms | 98ms | -2ms | -2.01
| getTeamMembersForUser | p99 | 489ms | 484ms | -5ms | -1.02
| getTeamsUnreadForUser | p99 | 996ms | 986ms | -10ms | -1.00
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 77ms| 77ms | 0s | 0.000
| BotStore.Get |  Avg| 112ms| 56ms | -56ms | -50.062
| |  P99| 2.14s| 770ms | -1.37s | -64.019
| ChannelBookmarkStore.Delete |  Avg| 48ms| 14ms | -34ms | -70.622
| |  P99| 234ms| 93ms | -141ms | -60.385
| ChannelBookmarkStore.Get |  Avg| 153ms| 78ms | -75ms | -48.944
| |  P99| 2.005s| 825ms | -1.18s | -58.853
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 421ms| 420ms | -1ms | -0.237
| ChannelBookmarkStore.Save |  Avg| 62ms| 64ms | 2ms | 3.205
| |  P99| 795ms| 1.675s | 880ms | 110.692
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 83ms| 106ms | 23ms | 27.687
| |  P99| 487ms| 960ms | 473ms | 97.026
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 69ms| 69ms | 0s | 0.000
| ChannelStore.AnalyticsCountAll |  Avg| 587ms| 357ms | -230ms | -39.179
| |  P99| 995ms| 975ms | -20ms | -2.010
| ChannelStore.Autocomplete |  Avg| 1.526s| 1.505s | -21ms | -1.376
| |  P99| 4.877s| 4.877s | 0s | 0.000
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 303ms| 278ms | -25ms | -8.254
| |  P99| 2.279s| 2.261s | -18ms | -0.790
| ChannelStore.CreateDirectChannel |  Avg| 184ms| 206ms | 22ms | 11.929
| |  P99| 2.208s| 2.21s | 2ms | 0.091
| ChannelStore.CreateInitialSidebarCategories |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 233ms| 227ms | -6ms | -2.572
| ChannelStore.CreateSidebarCategory |  Avg| 74ms| 73ms | -1ms | -1.358
| |  P99| 470ms| 480ms | 10ms | 2.128
| ChannelStore.Get |  Avg| 110ms| 112ms | 2ms | 1.816
| |  P99| 943ms| 949ms | 6ms | 0.636
| ChannelStore.GetAllChannelMembersForUser |  Avg| 35ms| 36ms | 1ms | 2.848
| |  P99| 482ms| 479ms | -3ms | -0.622
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 80ms| 61ms | -19ms | -23.624
| |  P99| 929ms| 742ms | -187ms | -20.121
| ChannelStore.GetByName |  Avg| 44ms| 45ms | 1ms | 2.253
| |  P99| 556ms| 577ms | 21ms | 3.777
| ChannelStore.GetChannelUnread |  Avg| 43ms| 40ms | -3ms | -7.058
| |  P99| 521ms| 556ms | 35ms | 6.722
| ChannelStore.GetChannels |  Avg| 61ms| 62ms | 1ms | 1.636
| |  P99| 799ms| 817ms | 18ms | 2.252
| ChannelStore.GetChannelsByIds |  Avg| 85ms| 0s | -85ms | -99.938
| |  P99| 945ms| 0s | -945ms | -99.997
| ChannelStore.GetChannelsByUser |  Avg| 35ms| 32ms | -3ms | -8.560
| |  P99| 474ms| 462ms | -12ms | -2.532
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 44ms| 45ms | 1ms | 2.251
| |  P99| 645ms| 660ms | 15ms | 2.327
| ChannelStore.GetFileCount |  Avg| 35ms| 36ms | 1ms | 2.851
| |  P99| 443ms| 452ms | 9ms | 2.031
| ChannelStore.GetGuestCount |  Avg| 66ms| 68ms | 2ms | 3.041
| |  P99| 803ms| 821ms | 18ms | 2.240
| ChannelStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 99ms| 100ms | 1ms | 1.006
| ChannelStore.GetMemberCount |  Avg| 246ms| 257ms | 11ms | 4.464
| |  P99| 1.094s| 1.239s | 145ms | 13.258
| ChannelStore.GetMemberCountsByGroup |  Avg| 16ms| 0s | -16ms | -100.797
| |  P99| 237ms| 0s | -237ms | -100.211
| ChannelStore.GetMemberForPost |  Avg| 69ms| 71ms | 2ms | 2.896
| |  P99| 865ms| 884ms | 19ms | 2.195
| ChannelStore.GetMemberLastViewedAt |  Avg| 29ms| 28ms | -1ms | -3.436
| |  P99| 461ms| 452ms | -9ms | -1.954
| ChannelStore.GetMembers |  Avg| 21ms| 143ms | 122ms | 574.592
| |  P99| 232ms| 935ms | 703ms | 302.983
| ChannelStore.GetMembersForUser |  Avg| 58ms| 58ms | 0s | 0.000
| |  P99| 771ms| 796ms | 25ms | 3.242
| ChannelStore.GetMembersForUserWithPagination |  Avg| 40ms| 39ms | -1ms | -2.477
| |  P99| 495ms| 493ms | -2ms | -0.404
| ChannelStore.GetPinnedPostCount |  Avg| 56ms| 58ms | 2ms | 3.557
| |  P99| 774ms| 824ms | 50ms | 6.464
| ChannelStore.GetPublicChannelsForTeam |  Avg| 86ms| 75ms | -11ms | -12.741
| |  P99| 853ms| 779ms | -74ms | -8.680
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 66ms| 62ms | -4ms | -6.052
| |  P99| 893ms| 869ms | -24ms | -2.688
| ChannelStore.GetSidebarCategory |  Avg| 111ms| 93ms | -18ms | -16.209
| |  P99| 1.33s| 905ms | -425ms | -31.955
| ChannelStore.GetTeamChannels |  Avg| 120ms| 89ms | -31ms | -25.740
| |  P99| 908ms| 890ms | -18ms | -1.983
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 6ms | 0s | 0.000
| |  P99| 80ms| 82ms | 2ms | 2.500
| ChannelStore.IsReadOnlyChannel |  Avg| 28ms| 28ms | 0s | 0.000
| |  P99| 459ms| 464ms | 5ms | 1.090
| ChannelStore.Save |  Avg| 95ms| 90ms | -5ms | -5.287
| |  P99| 975ms| 937ms | -38ms | -3.897
| ChannelStore.SaveMember |  Avg| 188ms| 194ms | 6ms | 3.195
| |  P99| 2.264s| 2.288s | 24ms | 1.060
| ChannelStore.SearchGroupChannels |  Avg| 65ms| 66ms | 1ms | 1.536
| |  P99| 812ms| 851ms | 39ms | 4.804
| ChannelStore.UpdateLastViewedAt |  Avg| 13ms| 13ms | 0s | 0.000
| |  P99| 144ms| 152ms | 8ms | 5.550
| ChannelStore.UpdateSidebarCategories |  Avg| 52ms| 60ms | 8ms | 15.325
| |  P99| 479ms| 441ms | -38ms | -7.937
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 72ms| 71ms | -1ms | -1.381
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 10ms| 11ms | 1ms | 10.344
| |  P99| 97ms| 163ms | 66ms | 67.991
| CommandWebhookStore.Cleanup |  Avg| 13ms| 20ms | 7ms | 55.647
| |  P99| 49ms| 97ms | 48ms | 97.959
| ComplianceStore.MessageExport |  Avg| 1ms| 1.258s | 1.257s | 120305.616
| |  P99| 5ms| 4.925s | 4.92s | 99370.082
| DesktopTokensStore.DeleteOlderThan |  Avg| 14ms| 2ms | -12ms | -87.674
| |  P99| 25ms| 5ms | -20ms | -80.483
| DraftStore.Delete |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 86ms| 94ms | 8ms | 9.299
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 48ms| 41ms | -7ms | -14.595
| |  P99| 200ms| 221ms | 21ms | 10.474
| DraftStore.Get |  Avg| 69ms| 71ms | 2ms | 2.895
| |  P99| 854ms| 873ms | 19ms | 2.224
| DraftStore.GetDraftsForUser |  Avg| 71ms| 63ms | -8ms | -11.224
| |  P99| 894ms| 788ms | -106ms | -11.863
| DraftStore.Upsert |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 96ms| 96ms | 0s | 0.000
| EmojiStore.GetByName |  Avg| 57ms| 57ms | 0s | 0.000
| |  P99| 796ms| 817ms | 21ms | 2.637
| EmojiStore.GetMultipleByName |  Avg| 4ms| 109ms | 105ms | 2632.450
| |  P99| 23ms| 476ms | 453ms | 1991.206
| EmojiStore.Search |  Avg| 1ms| 0s | -1ms | -151.524
| |  P99| 5ms| 0s | -5ms | -101.010
| FileInfoStore.AttachToPost |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 95ms| 87ms | -8ms | -8.381
| FileInfoStore.Get |  Avg| 34ms| 35ms | 1ms | 2.910
| |  P99| 472ms| 478ms | 6ms | 1.270
| FileInfoStore.GetByIds |  Avg| 63ms| 61ms | -2ms | -3.190
| |  P99| 878ms| 827ms | -51ms | -5.806
| FileInfoStore.GetForPost |  Avg| 69ms| 61ms | -8ms | -11.599
| |  P99| 917ms| 876ms | -41ms | -4.472
| FileInfoStore.Save |  Avg| 11ms| 11ms | 0s | 0.000
| |  P99| 100ms| 98ms | -2ms | -2.002
| FileInfoStore.SetContent |  Avg| 16ms| 15ms | -1ms | -6.309
| |  P99| 176ms| 136ms | -40ms | -22.686
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 36ms| 37ms | 1ms | 2.805
| |  P99| 485ms| 485ms | 0s | 0.000
| GroupStore.GetByName |  Avg| 37ms| 36ms | -1ms | -2.726
| |  P99| 470ms| 465ms | -5ms | -1.063
| GroupStore.GetGroups |  Avg| 57ms| 58ms | 1ms | 1.755
| |  P99| 797ms| 805ms | 8ms | 1.003
| JobStore.GetAllByStatus |  Avg| 62ms| 64ms | 2ms | 3.232
| |  P99| 805ms| 827ms | 22ms | 2.734
| JobStore.GetAllByTypePage |  Avg| 67ms| 301ms | 234ms | 350.432
| |  P99| 898ms| 980ms | 82ms | 9.128
| JobStore.GetCountByStatusAndType |  Avg| 62ms| 40ms | -22ms | -35.537
| |  P99| 489ms| 685ms | 196ms | 40.041
| JobStore.GetNewestJobByStatusesAndType |  Avg| 50ms| 41ms | -9ms | -17.881
| |  P99| 480ms| 620ms | 140ms | 29.167
| JobStore.Save |  Avg| 8ms| 6ms | -2ms | -24.236
| |  P99| 79ms| 40ms | -39ms | -49.576
| JobStore.UpdateOptimistically |  Avg| 8ms| 9ms | 1ms | 12.261
| |  P99| 84ms| 84ms | 0s | 0.000
| JobStore.UpdateStatus |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 93ms| 69ms | -24ms | -25.807
| JobStore.UpdateStatusOptimistically |  Avg| 18ms| 19ms | 1ms | 5.437
| |  P99| 186ms| 213ms | 27ms | 14.516
| LicenseStore.GetAll |  Avg| 71ms| 13ms | -58ms | -81.590
| |  P99| 100ms| 97ms | -3ms | -3.015
| LinkMetadataStore.Get |  Avg| 51ms| 53ms | 2ms | 3.926
| |  P99| 751ms| 770ms | 19ms | 2.530
| LinkMetadataStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 118ms| 76ms | -42ms | -35.593
| PluginStore.List |  Avg| 73ms| 51ms | -22ms | -30.169
| |  P99| 1.06s| 770ms | -290ms | -27.358
| PostAcknowledgementStore.GetForPost |  Avg| 45ms| 45ms | 0s | 0.000
| |  P99| 651ms| 684ms | 33ms | 5.071
| PostAcknowledgementStore.GetForPosts |  Avg| 73ms| 75ms | 2ms | 2.744
| |  P99| 1.28s| 1.343s | 63ms | 4.921
| PostPersistentNotificationStore.DeleteExpired |  Avg| 4ms| 7ms | 3ms | 80.492
| |  P99| 40ms| 138ms | 98ms | 242.728
| PostPersistentNotificationStore.Get |  Avg| 6ms| 8ms | 2ms | 33.796
| |  P99| 85ms| 138ms | 53ms | 62.231
| PostPersistentNotificationStore.GetSingle |  Avg| 60ms| 59ms | -1ms | -1.676
| |  P99| 818ms| 842ms | 24ms | 2.935
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 22ms| 0s | -22ms | -100.342
| |  P99| 235ms| 0s | -235ms | -99.997
| PostPriorityStore.GetForPost |  Avg| 47ms| 52ms | 5ms | 10.574
| |  P99| 678ms| 844ms | 166ms | 24.500
| PostPriorityStore.GetForPosts |  Avg| 76ms| 79ms | 3ms | 3.937
| |  P99| 1.344s| 1.427s | 83ms | 6.177
| PostStore.AnalyticsPostCount |  Avg| 1.007s| 1.231s | 224ms | 22.235
| |  P99| 2.471s| 2.48s | 9ms | 0.364
| PostStore.AnalyticsPostCountByTeam |  Avg| 1.627s| 1.275s | -352ms | -21.639
| |  P99| 2.485s| 2.475s | -10ms | -0.402
| PostStore.Delete |  Avg| 77ms| 49ms | -28ms | -36.141
| |  P99| 459ms| 805ms | 346ms | 75.423
| PostStore.Get |  Avg| 106ms| 107ms | 1ms | 0.939
| |  P99| 1.415s| 1.429s | 14ms | 0.989
| PostStore.GetEtag |  Avg| 57ms| 58ms | 1ms | 1.753
| |  P99| 739ms| 747ms | 8ms | 1.082
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 61ms| 61ms | 0s | 0.000
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 83ms| 84ms | 1ms | 1.204
| PostStore.GetPostReminderMetadata |  Avg| 75ms| 70ms | -5ms | -6.637
| |  P99| 1.517s| 845ms | -672ms | -44.283
| PostStore.GetPostReminders |  Avg| 17ms| 19ms | 2ms | 11.824
| |  P99| 180ms| 216ms | 36ms | 20.056
| PostStore.GetPosts |  Avg| 28ms| 27ms | -1ms | -3.540
| |  P99| 435ms| 418ms | -17ms | -3.905
| PostStore.GetPostsAfter |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 754ms| 778ms | 24ms | 3.184
| PostStore.GetPostsBefore |  Avg| 52ms| 52ms | 0s | 0.000
| |  P99| 707ms| 710ms | 3ms | 0.424
| PostStore.GetPostsByIds |  Avg| 43ms| 0s | -43ms | -99.145
| |  P99| 243ms| 0s | -243ms | -100.206
| PostStore.GetPostsByThread |  Avg| 57ms| 59ms | 2ms | 3.486
| |  P99| 825ms| 825ms | 0s | 0.000
| PostStore.GetPostsSince |  Avg| 77ms| 79ms | 2ms | 2.584
| |  P99| 824ms| 838ms | 14ms | 1.699
| PostStore.GetSingle |  Avg| 50ms| 51ms | 1ms | 2.019
| |  P99| 743ms| 763ms | 20ms | 2.692
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 27ms| 27ms | 0s | 0.000
| |  P99| 232ms| 233ms | 1ms | 0.431
| PostStore.SearchPostsForUser |  Avg| 118ms| 105ms | -13ms | -11.002
| |  P99| 1.085s| 975ms | -110ms | -10.140
| PostStore.SetPostReminder |  Avg| 25ms| 21ms | -4ms | -15.811
| |  P99| 225ms| 380ms | 155ms | 68.812
| PostStore.Update |  Avg| 28ms| 31ms | 3ms | 10.812
| |  P99| 191ms| 225ms | 34ms | 17.834
| PreferenceStore.DeleteCategoryAndName |  Avg| 8ms| 7ms | -1ms | -12.697
| |  P99| 83ms| 47ms | -36ms | -43.114
| PreferenceStore.Get |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 698ms| 712ms | 14ms | 2.006
| PreferenceStore.GetAll |  Avg| 54ms| 53ms | -1ms | -1.852
| |  P99| 705ms| 705ms | 0s | 0.000
| PreferenceStore.Save |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 219ms| 218ms | -1ms | -0.456
| ProductNoticesStore.ClearOldNotices |  Avg| 3ms| 2ms | -1ms | -37.810
| |  P99| 5ms| 5ms | 0s | 0.000
| ProductNoticesStore.View |  Avg| 58ms| 58ms | 0s | 0.000
| |  P99| 387ms| 395ms | 8ms | 2.070
| PropertyFieldStore.SearchPropertyFields |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 432ms| 447ms | 15ms | 3.475
| PropertyValueStore.SearchPropertyValues |  Avg| 60ms| 69ms | 9ms | 15.037
| |  P99| 803ms| 884ms | 81ms | 10.082
| ReactionStore.GetForPost |  Avg| 54ms| 55ms | 1ms | 1.851
| |  P99| 805ms| 740ms | -65ms | -8.075
| RetentionPolicyStore.GetAll |  Avg| 55ms| 0s | -55ms | -100.332
| |  P99| 100ms| 0s | -100ms | -100.503
| RetentionPolicyStore.GetCount |  Avg| 48ms| 0s | -48ms | -100.821
| |  P99| 50ms| 0s | -50ms | -100.503
| RoleStore.ChannelHigherScopedPermissions |  Avg| 18ms| 154ms | 136ms | 773.584
| |  P99| 132ms| 990ms | 858ms | 652.471
| RoleStore.GetByNames |  Avg| 20ms| 179ms | 159ms | 808.649
| |  P99| 222ms| 952ms | 730ms | 328.182
| ScheduledPostStore.CreateScheduledPost |  Avg| 8ms| 9ms | 1ms | 12.957
| |  P99| 69ms| 82ms | 13ms | 18.909
| ScheduledPostStore.Get |  Avg| 9ms| 0s | -9ms | -96.174
| |  P99| 25ms| 0s | -25ms | -101.187
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 124ms| 61ms | -63ms | -50.838
| |  P99| 1.795s| 472ms | -1.323s | -73.705
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 33ms| 31ms | -2ms | -6.017
| |  P99| 470ms| 446ms | -24ms | -5.105
| ScheduledPostStore.PermanentlyDeleteScheduledPosts |  Avg| 4ms| 0s | -4ms | -100.731
| |  P99| 5ms| 0s | -5ms | -100.967
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 9ms| 5ms | -4ms | -47.031
| |  P99| 88ms| 77ms | -11ms | -12.465
| SchemeStore.GetAllPage |  Avg| 73ms| 1ms | -72ms | -99.301
| |  P99| 100ms| 5ms | -95ms | -95.477
| SessionStore.Get |  Avg| 48ms| 49ms | 1ms | 2.062
| |  P99| 586ms| 573ms | -13ms | -2.218
| SessionStore.GetLRUSessions |  Avg| 35ms| 34ms | -1ms | -2.820
| |  P99| 480ms| 471ms | -9ms | -1.877
| SessionStore.GetSessionsExpired |  Avg| 54ms| 39ms | -15ms | -27.574
| |  P99| 450ms| 476ms | 26ms | 5.778
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 43ms| 44ms | 1ms | 2.303
| |  P99| 678ms| 699ms | 21ms | 3.097
| SessionStore.Remove |  Avg| 6ms| 8ms | 2ms | 35.564
| |  P99| 32ms| 84ms | 52ms | 160.002
| SessionStore.Save |  Avg| 40ms| 39ms | -1ms | -2.529
| |  P99| 479ms| 465ms | -14ms | -2.926
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 73ms| 77ms | 4ms | 5.469
| SharedChannelStore.HasChannel |  Avg| 31ms| 31ms | 0s | 0.000
| |  P99| 469ms| 469ms | 0s | 0.000
| StatusStore.Get |  Avg| 50ms| 49ms | -1ms | -2.007
| |  P99| 699ms| 653ms | -46ms | -6.583
| StatusStore.GetByIds |  Avg| 77ms| 80ms | 3ms | 3.894
| |  P99| 898ms| 925ms | 27ms | 3.007
| StatusStore.SaveOrUpdate |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 92ms| 93ms | 1ms | 1.086
| StatusStore.SaveOrUpdateMany |  Avg| 11ms| 12ms | 1ms | 9.150
| |  P99| 122ms| 158ms | 36ms | 29.508
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 22ms| 26ms | 4ms | 18.584
| |  P99| 217ms| 239ms | 22ms | 10.138
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 88ms | 4ms | 4.784
| SystemStore.Get |  Avg| 1ms| 0s | -1ms | -85.827
| |  P99| 5ms| 0s | -5ms | -101.010
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 66ms| 68ms | 2ms | 3.042
| TeamStore.AnalyticsTeamCount |  Avg| 56ms| 119ms | 63ms | 111.779
| |  P99| 100ms| 488ms | 388ms | 389.950
| TeamStore.Get |  Avg| 48ms| 50ms | 2ms | 4.161
| |  P99| 732ms| 748ms | 16ms | 2.185
| TeamStore.GetActiveMemberCount |  Avg| 308ms| 230ms | -78ms | -25.329
| |  P99| 1.96s| 945ms | -1.015s | -51.786
| TeamStore.GetAllPage |  Avg| 40ms| 40ms | 0s | 0.000
| |  P99| 499ms| 502ms | 3ms | 0.602
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 40ms| 40ms | 0s | 0.000
| |  P99| 499ms| 513ms | 14ms | 2.804
| TeamStore.GetMany |  Avg| 29ms| 0s | -29ms | -98.728
| |  P99| 241ms| 0s | -241ms | -100.000
| TeamStore.GetMember |  Avg| 14ms| 15ms | 1ms | 6.955
| |  P99| 249ms| 265ms | 16ms | 6.413
| TeamStore.GetTeamsByUserId |  Avg| 41ms| 40ms | -1ms | -2.453
| |  P99| 495ms| 500ms | 5ms | 1.010
| TeamStore.GetTeamsForUser |  Avg| 37ms| 35ms | -2ms | -5.454
| |  P99| 482ms| 472ms | -10ms | -2.075
| TeamStore.GetTotalMemberCount |  Avg| 244ms| 190ms | -54ms | -22.132
| |  P99| 940ms| 489ms | -451ms | -47.979
| TeamStore.SaveMember |  Avg| 128ms| 130ms | 2ms | 1.563
| |  P99| 731ms| 765ms | 34ms | 4.649
| ThreadStore.Get |  Avg| 66ms| 67ms | 1ms | 1.522
| |  P99| 869ms| 862ms | -7ms | -0.806
| ThreadStore.GetMembershipForUser |  Avg| 58ms| 57ms | -1ms | -1.735
| |  P99| 817ms| 808ms | -9ms | -1.102
| ThreadStore.GetTeamsUnreadForUser |  Avg| 53ms| 52ms | -1ms | -1.900
| |  P99| 841ms| 825ms | -16ms | -1.902
| ThreadStore.GetThreadFollowers |  Avg| 58ms| 57ms | -1ms | -1.736
| |  P99| 816ms| 823ms | 7ms | 0.858
| ThreadStore.GetThreadForUser |  Avg| 74ms| 76ms | 2ms | 2.712
| |  P99| 977ms| 980ms | 3ms | 0.307
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 61ms| 63ms | 2ms | 3.286
| |  P99| 822ms| 857ms | 35ms | 4.257
| ThreadStore.GetThreadsForUser |  Avg| 64ms| 65ms | 1ms | 1.560
| |  P99| 820ms| 834ms | 14ms | 1.707
| ThreadStore.GetTotalThreads |  Avg| 38ms| 37ms | -1ms | -2.642
| |  P99| 493ms| 486ms | -7ms | -1.421
| ThreadStore.GetTotalUnreadMentions |  Avg| 41ms| 40ms | -1ms | -2.452
| |  P99| 583ms| 564ms | -19ms | -3.261
| ThreadStore.GetTotalUnreadThreads |  Avg| 38ms| 37ms | -1ms | -2.622
| |  P99| 496ms| 494ms | -2ms | -0.403
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 38ms| 37ms | -1ms | -2.622
| |  P99| 497ms| 488ms | -9ms | -1.811
| ThreadStore.MaintainMembership |  Avg| 15ms| 16ms | 1ms | 6.501
| |  P99| 189ms| 191ms | 2ms | 1.059
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 88ms| 92ms | 4ms | 4.533
| ThreadStore.MarkAllAsReadByTeam |  Avg| 14ms| 20ms | 6ms | 42.549
| |  P99| 95ms| 96ms | 1ms | 1.053
| ThreadStore.MarkAsRead |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 77ms| 86ms | 9ms | 11.632
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 88ms| 91ms | 3ms | 3.414
| TokenStore.Cleanup |  Avg| 25ms| 10ms | -15ms | -61.000
| |  P99| 238ms| 48ms | -190ms | -79.832
| UserAccessTokenStore.GetByToken |  Avg| 32ms| 45ms | 13ms | 40.918
| |  P99| 710ms| 840ms | 130ms | 18.310
| UserStore.AnalyticsActiveCount |  Avg| 550ms| 631ms | 81ms | 14.728
| |  P99| 990ms| 2.35s | 1.36s | 137.374
| UserStore.AnalyticsGetInactiveUsersCount |  Avg| 340ms| 103ms | -237ms | -69.649
| |  P99| 497ms| 246ms | -251ms | -50.452
| UserStore.AutocompleteUsersInChannel |  Avg| 400ms| 390ms | -10ms | -2.502
| |  P99| 2.051s| 2.022s | -29ms | -1.414
| UserStore.Count |  Avg| 189ms| 189ms | 0s | 0.000
| |  P99| 892ms| 886ms | -6ms | -0.673
| UserStore.Get |  Avg| 36ms| 37ms | 1ms | 2.813
| |  P99| 501ms| 544ms | 43ms | 8.587
| UserStore.GetAllProfiles |  Avg| 35ms| 34ms | -1ms | -2.864
| |  P99| 481ms| 482ms | 1ms | 0.208
| UserStore.GetAllProfilesInChannel |  Avg| 722ms| 724ms | 2ms | 0.277
| |  P99| 2.45s| 2.449s | -1ms | -0.041
| UserStore.GetByUsername |  Avg| 52ms| 48ms | -4ms | -7.629
| |  P99| 682ms| 713ms | 31ms | 4.544
| UserStore.GetForLogin |  Avg| 37ms| 36ms | -1ms | -2.669
| |  P99| 476ms| 469ms | -7ms | -1.470
| UserStore.GetMany |  Avg| 45ms| 49ms | 4ms | 8.943
| |  P99| 489ms| 486ms | -3ms | -0.613
| UserStore.GetProfileByGroupChannelIdsForUser |  Avg| 2ms| 3ms | 1ms | 48.704
| |  P99| 5ms| 5ms | 0s | 0.000
| UserStore.GetProfileByIds |  Avg| 43ms| 43ms | 0s | 0.000
| |  P99| 610ms| 626ms | 16ms | 2.622
| UserStore.GetProfilesByUsernames |  Avg| 39ms| 38ms | -1ms | -2.595
| |  P99| 487ms| 488ms | 1ms | 0.205
| UserStore.GetProfilesInChannel |  Avg| 88ms| 52ms | -36ms | -41.036
| |  P99| 785ms| 479ms | -306ms | -38.981
| UserStore.GetProfilesNotInChannel |  Avg| 90ms| 30ms | -60ms | -67.014
| |  P99| 485ms| 234ms | -251ms | -51.742
| UserStore.GetUnreadCount |  Avg| 45ms| 46ms | 1ms | 2.217
| |  P99| 692ms| 709ms | 17ms | 2.458
| UserStore.IsEmpty |  Avg| 25ms| 25ms | 0s | 0.000
| |  P99| 416ms| 410ms | -6ms | -1.444
| UserStore.Save |  Avg| 89ms| 89ms | 0s | 0.000
| |  P99| 289ms| 302ms | 13ms | 4.499
| UserStore.Search |  Avg| 182ms| 179ms | -3ms | -1.650
| |  P99| 975ms| 970ms | -5ms | -0.513
| UserStore.Update |  Avg| 15ms| 16ms | 1ms | 6.625
| |  P99| 105ms| 100ms | -5ms | -4.751
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 80ms | 1ms | 1.266
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 64ms| 58ms | -6ms | -9.333
| UserStore.UpdateUpdateAt |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 71ms| 75ms | 4ms | 5.606
| UserTermsOfServiceStore.GetByUser |  Avg| 43ms| 42ms | -1ms | -2.349
| |  P99| 546ms| 592ms | 46ms | 8.423
| WebhookStore.GetOutgoingByTeam |  Avg| 60ms| 60ms | 0s | 0.000
| |  P99| 789ms| 794ms | 5ms | 0.634
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 1.105s| 1.006s | -99ms | -8.963
| | P99| 9.23s| 7.667s | -1.563s | -16.935
| addTeamMember | Avg| 2.134s| 2.193s | 59ms | 2.765
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 303ms| 279ms | -24ms | -7.922
| | P99| 2.279s| 2.261s | -18ms | -0.790
| autocompleteEmojis | Avg| 1ms| 0s | -1ms | -142.389
| | P99| 5ms| 0s | -5ms | -101.010
| autocompleteUsers | Avg| 347ms| 334ms | -13ms | -3.749
| | P99| 2.09s| 2.07s | -20ms | -0.957
| channelMemberCountsByGroup | Avg| 16ms| 0s | -16ms | -99.964
| | P99| 237ms| 0s | -237ms | -100.211
| createCategoryForTeamForUser | Avg| 142ms| 190ms | 48ms | 33.911
| | P99| 490ms| 960ms | 470ms | 95.918
| createChannel | Avg| 1.246s| 731ms | -515ms | -41.319
| | P99| 8.15s| 4.45s | -3.7s | -45.398
| createChannelBookmark | Avg| 99ms| 103ms | 4ms | 4.046
| | P99| 835ms| 1.855s | 1.02s | 122.156
| createDirectChannel | Avg| 626ms| 683ms | 57ms | 9.110
| | P99| 4.033s| 4.506s | 473ms | 11.727
| createGroupChannel | Avg| 1.216s| 1.247s | 31ms | 2.549
| | P99| 7.931s| 8.925s | 994ms | 12.533
| createPost | Avg| 1.014s| 1.028s | 14ms | 1.381
| | P99| 8.289s| 8.421s | 132ms | 1.592
| createSchedulePost | Avg| 13ms| 29ms | 16ms | 126.032
| | P99| 213ms| 247ms | 34ms | 16.000
| createUser | Avg| 676ms| 674ms | -2ms | -0.296
| | P99| 3.318s| 3.528s | 210ms | 6.329
| deleteChannelBookmark | Avg| 114ms| 109ms | -5ms | -4.370
| | P99| 247ms| 493ms | 246ms | 99.577
| deleteDraft | Avg| 70ms| 72ms | 2ms | 2.872
| | P99| 855ms| 874ms | 19ms | 2.222
| deletePost | Avg| 291ms| 103ms | -188ms | -64.539
| | P99| 4.175s| 903ms | -3.272s | -78.372
| deleteScheduledPost | Avg| 5ms| 0s | -5ms | -107.664
| | P99| 5ms| 0s | -5ms | -100.967
| followThreadByUser | Avg| 186ms| 153ms | -33ms | -17.716
| | P99| 1.96s| 1.615s | -345ms | -17.602
| getAllTeams | Avg| 43ms| 43ms | 0s | 0.000
| | P99| 586ms| 568ms | -18ms | -3.073
| getAnalytics | Avg| 2.273s| 1.823s | -450ms | -19.795
| | P99| 2.485s| 4.925s | 2.44s | 98.189
| getCategoriesForTeamForUser | Avg| 67ms| 63ms | -4ms | -6.000
| | P99| 896ms| 874ms | -22ms | -2.455
| getChannel | Avg| 110ms| 125ms | 15ms | 13.662
| | P99| 1.259s| 1.887s | 628ms | 49.891
| getChannelMember | Avg| 49ms| 50ms | 1ms | 2.046
| | P99| 848ms| 854ms | 6ms | 0.708
| getChannelMembers | Avg| 26ms| 152ms | 126ms | 489.536
| | P99| 232ms| 935ms | 703ms | 302.983
| getChannelMembersForTeamForUser | Avg| 58ms| 58ms | 0s | 0.000
| | P99| 772ms| 796ms | 24ms | 3.111
| getChannelMembersForUser | Avg| 41ms| 39ms | -2ms | -4.938
| | P99| 495ms| 494ms | -1ms | -0.202
| getChannelStats | Avg| 32ms| 34ms | 2ms | 6.266
| | P99| 807ms| 840ms | 33ms | 4.090
| getChannelUnread | Avg| 46ms| 44ms | -2ms | -4.366
| | P99| 620ms| 638ms | 18ms | 2.904
| getChannelsForTeamForUser | Avg| 61ms| 62ms | 1ms | 1.633
| | P99| 799ms| 816ms | 17ms | 2.128
| getChannelsForUser | Avg| 35ms| 33ms | -2ms | -5.682
| | P99| 474ms| 463ms | -11ms | -2.320
| getClientConfig | Avg| 20ms| 19ms | -1ms | -5.076
| | P99| 244ms| 243ms | -1ms | -0.409
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getDrafts | Avg| 76ms| 67ms | -9ms | -11.836
| | P99| 932ms| 855ms | -77ms | -8.264
| getFilePreview | Avg| 86ms| 86ms | 0s | 0.000
| | P99| 686ms| 702ms | 16ms | 2.331
| getFileThumbnail | Avg| 83ms| 83ms | 0s | 0.000
| | P99| 745ms| 764ms | 19ms | 2.551
| getFilteredUsersStats | Avg| 368ms| 295ms | -73ms | -19.857
| | P99| 497ms| 980ms | 483ms | 97.085
| getJobsByType | Avg| 67ms| 301ms | 234ms | 347.653
| | P99| 898ms| 980ms | 82ms | 9.128
| getPostThread | Avg| 330ms| 337ms | 7ms | 2.119
| | P99| 3.745s| 3.603s | -142ms | -3.792
| getPostsForChannel | Avg| 541ms| 561ms | 20ms | 3.699
| | P99| 8.842s| 9.091s | 249ms | 2.816
| getPostsForChannelAroundLastUnread | Avg| 168ms| 163ms | -5ms | -2.971
| | P99| 2.399s| 2.385s | -14ms | -0.583
| getPreferences | Avg| 55ms| 53ms | -2ms | -3.654
| | P99| 716ms| 715ms | -1ms | -0.140
| getPrevTrialLicense | Avg| 58ms| 18ms | -40ms | -68.746
| | P99| 100ms| 98ms | -2ms | -2.010
| getProfileImage | Avg| 87ms| 83ms | -4ms | -4.618
| | P99| 484ms| 487ms | 3ms | 0.620
| getPublicChannelsForTeam | Avg| 87ms| 76ms | -11ms | -12.586
| | P99| 853ms| 779ms | -74ms | -8.680
| getRolesByNames | Avg| 117ms| 42ms | -75ms | -64.288
| | P99| 247ms| 935ms | 688ms | 278.543
| getTeamMember | Avg| 8ms| 9ms | 1ms | 12.059
| | P99| 128ms| 136ms | 8ms | 6.236
| getTeamMembersForUser | Avg| 38ms| 37ms | -1ms | -2.603
| | P99| 489ms| 484ms | -5ms | -1.022
| getTeamScheduledPosts | Avg| 67ms| 62ms | -5ms | -7.487
| | P99| 922ms| 861ms | -61ms | -6.617
| getTeamStats | Avg| 321ms| 244ms | -77ms | -24.012
| | P99| 1.96s| 945ms | -1.015s | -51.786
| getTeamsForUser | Avg| 41ms| 40ms | -1ms | -2.446
| | P99| 495ms| 500ms | 5ms | 1.010
| getTeamsUnreadForUser | Avg| 74ms| 72ms | -2ms | -2.706
| | P99| 996ms| 986ms | -10ms | -1.005
| getThreadsForUser | Avg| 63ms| 64ms | 1ms | 1.586
| | P99| 848ms| 854ms | 6ms | 0.707
| getUser | Avg| 63ms| 66ms | 3ms | 4.736
| | P99| 856ms| 918ms | 62ms | 7.246
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 1ms| 1ms | 0s | 0.000
| | P99| 24ms| 23ms | -1ms | -4.253
| getUsers | Avg| 35ms| 37ms | 2ms | 5.792
| | P99| 498ms| 621ms | 123ms | 24.684
| getUsersByIds | Avg| 5ms| 5ms | 0s | 0.000
| | P99| 141ms| 142ms | 1ms | 0.711
| getUsersByNames | Avg| 39ms| 39ms | 0s | 0.000
| | P99| 491ms| 491ms | 0s | 0.000
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 32ms| 31ms | -1ms | -3.171
| | P99| 456ms| 468ms | 12ms | 2.631
| listCPAValues | Avg| 63ms| 73ms | 10ms | 15.892
| | P99| 833ms| 906ms | 73ms | 8.766
| listChannelBookmarksForChannel | Avg| 29ms| 30ms | 1ms | 3.401
| | P99| 484ms| 482ms | -2ms | -0.414
| login | Avg| 193ms| 189ms | -4ms | -2.068
| | P99| 2.042s| 1.993s | -49ms | -2.400
| logout | Avg| 92ms| 188ms | 96ms | 104.598
| | P99| 1.45s| 2.185s | 735ms | 50.689
| patchPost | Avg| 361ms| 389ms | 28ms | 7.759
| | P99| 3.858s| 4.158s | 300ms | 7.775
| removeUserCustomStatus | Avg| 315ms| 297ms | -18ms | -5.714
| | P99| 2.6s| 2.435s | -165ms | -6.346
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 182ms| 185ms | 3ms | 1.646
| | P99| 2.227s| 2.251s | 24ms | 1.077
| searchAllChannels | Avg| 1.528s| 1.507s | -21ms | -1.374
| | P99| 4.877s| 4.877s | 0s | 0.000
| searchGroupChannels | Avg| 65ms| 67ms | 2ms | 3.066
| | P99| 812ms| 851ms | 39ms | 4.804
| searchPostsInTeam | Avg| 225ms| 198ms | -27ms | -11.980
| | P99| 3.052s| 2.605s | -447ms | -14.646
| searchUsers | Avg| 183ms| 181ms | -2ms | -1.093
| | P99| 977ms| 974ms | -3ms | -0.307
| setPostReminder | Avg| 178ms| 305ms | 127ms | 71.369
| | P99| 2.005s| 3.8s | 1.795s | 89.526
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 143ms| 160ms | 17ms | 11.929
| | P99| 1.656s| 1.808s | 152ms | 9.180
| updateCategoriesForTeamForUser | Avg| 324ms| 285ms | -39ms | -12.032
| | P99| 3.538s| 2.358s | -1.18s | -33.357
| updateChannelBookmark | Avg| 454ms| 172ms | -282ms | -62.078
| | P99| 4.7s| 975ms | -3.725s | -79.256
| updateChannelBookmarkSortOrder | Avg| 149ms| 142ms | -7ms | -4.683
| | P99| 493ms| 970ms | 477ms | 96.689
| updatePreferences | Avg| 28ms| 29ms | 1ms | 3.509
| | P99| 246ms| 247ms | 1ms | 0.407
| updateReadStateAllThreadsByUser | Avg| 14ms| 20ms | 6ms | 42.199
| | P99| 95ms| 96ms | 1ms | 1.053
| updateReadStateThreadByUser | Avg| 504ms| 524ms | 20ms | 3.968
| | P99| 4.747s| 4.769s | 22ms | 0.463
| updateUserCustomStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 553ms| 518ms | -35ms | -6.326
| | P99| 2.16s| 2.002s | -158ms | -7.314
| upsertDraft | Avg| 34ms| 34ms | 0s | 0.000
| | P99| 571ms| 573ms | 2ms | 0.350
| viewChannel | Avg| 171ms| 177ms | 6ms | 3.499
| | P99| 2.358s| 2.409s | 51ms | 2.162
