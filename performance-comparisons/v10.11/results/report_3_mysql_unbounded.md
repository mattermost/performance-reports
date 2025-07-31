### Store times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| UserStore.GetProfilesNotInChannel | avg | 42ms | 218ms | 176ms | 417.49
| DesktopTokensStore.DeleteOlderThan | avg | 2ms | 10ms | 8ms | 364.71
| SessionStore.GetSessionsExpired | avg | 35ms | 160ms | 125ms | 357.68
| ChannelBookmarkStore.Get | avg | 30ms | 129ms | 99ms | 335.40
| ChannelBookmarkStore.Delete | avg | 10ms | 35ms | 25ms | 241.52
| ChannelStore.GetMembers | avg | 36ms | 67ms | 31ms | 85.28
| ScheduledPostStore.UpdateOldScheduledPosts | avg | 3ms | 5ms | 2ms | 63.50
| PostStore.Delete | avg | 75ms | 122ms | 47ms | 62.60
| PostStore.SetPostReminder | avg | 12ms | 19ms | 7ms | 60.79
| UserStore.GetMany | avg | 52ms | 78ms | 26ms | 50.08
| ChannelStore.CreateSidebarCategory | avg | 40ms | 59ms | 19ms | 47.84
| JobStore.GetCountByStatusAndType | avg | 35ms | 50ms | 15ms | 42.54
| PreferenceStore.DeleteCategoryAndName | avg | 5ms | 7ms | 2ms | 36.56
| ClusterDiscoveryStore.SetLastPingAt | avg | 11ms | 15ms | 4ms | 35.79
| StatusStore.UpdateExpiredDNDStatuses | avg | 12ms | 16ms | 4ms | 32.12
| DraftStore.GetDraftsForUser | avg | 54ms | 71ms | 17ms | 31.30
| JobStore.UpdateStatus | avg | 7ms | 9ms | 2ms | 30.73
| JobStore.UpdateOptimistically | avg | 7ms | 9ms | 2ms | 29.30
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | avg | 59ms | 73ms | 14ms | 23.71
| StatusStore.Get | avg | 45ms | 52ms | 7ms | 15.43
| ChannelStore.GetByName | avg | 39ms | 45ms | 6ms | 15.37
| FileInfoStore.GetForPost | avg | 65ms | 75ms | 10ms | 15.36
| UserStore.GetProfileByIds | avg | 39ms | 45ms | 6ms | 15.27
| PostPriorityStore.GetForPost | avg | 46ms | 53ms | 7ms | 15.26
| ThreadStore.GetTeamsUnreadForUser | avg | 46ms | 53ms | 7ms | 15.24
| ChannelBookmarkStore.Save | avg | 46ms | 53ms | 7ms | 15.10
| TeamStore.GetMember | avg | 13ms | 15ms | 2ms | 14.99
| BotStore.Get | avg | 34ms | 39ms | 5ms | 14.72
| ScheduledPostStore.GetScheduledPostsForUser | avg | 28ms | 32ms | 4ms | 14.35
| SessionStore.Get | avg | 43ms | 49ms | 6ms | 13.80
| ChannelStore.GetMemberForPost | avg | 62ms | 70ms | 8ms | 12.98
| JobStore.GetAllByStatus | avg | 54ms | 61ms | 7ms | 12.98
| LinkMetadataStore.Get | avg | 46ms | 52ms | 6ms | 12.93
| GroupStore.GetByName | avg | 31ms | 35ms | 4ms | 12.86
| ChannelStore.GetChannels | avg | 55ms | 62ms | 7ms | 12.70
| DraftStore.Get | avg | 63ms | 71ms | 8ms | 12.61
| TeamStore.GetTeamsForUser | avg | 32ms | 36ms | 4ms | 12.50
| EmojiStore.GetByName | avg | 49ms | 55ms | 6ms | 12.25
| ChannelStore.SearchGroupChannels | avg | 57ms | 64ms | 7ms | 12.25
| DraftStore.DeleteDraftsAssociatedWithPost | avg | 41ms | 46ms | 5ms | 12.14
| UserStore.Get | avg | 33ms | 37ms | 4ms | 12.11
| PropertyFieldStore.SearchPropertyFields | avg | 25ms | 28ms | 3ms | 11.89
| ChannelStore.CreateDirectChannel | avg | 178ms | 199ms | 21ms | 11.82
| GroupStore.GetGroups | avg | 51ms | 57ms | 6ms | 11.77
| ThreadStore.GetTotalUnreadThreads | avg | 34ms | 38ms | 4ms | 11.67
| ThreadStore.GetTotalThreads | avg | 34ms | 38ms | 4ms | 11.60
| TeamStore.GetAllPage | avg | 35ms | 39ms | 4ms | 11.50
| ChannelStore.GetMembersForUser | avg | 52ms | 58ms | 6ms | 11.48
| ChannelStore.GetMemberLastViewedAt | avg | 26ms | 29ms | 3ms | 11.46
| TeamStore.Get | avg | 44ms | 49ms | 5ms | 11.43
| PostStore.GetEtag | avg | 53ms | 59ms | 6ms | 11.35
| PostStore.Get | avg | 97ms | 108ms | 11ms | 11.34
| PreferenceStore.Get | avg | 44ms | 49ms | 5ms | 11.33
| TeamStore.GetChannelUnreadsForAllTeams | avg | 36ms | 40ms | 4ms | 11.21
| PostStore.GetSingle | avg | 45ms | 50ms | 5ms | 11.10
| TeamStore.GetTeamsByUserId | avg | 36ms | 40ms | 4ms | 11.04
| ThreadStore.GetThreadUnreadReplyCount | avg | 55ms | 61ms | 6ms | 10.94
| UserTermsOfServiceStore.GetByUser | avg | 37ms | 41ms | 4ms | 10.74
| PostAcknowledgementStore.GetForPosts | avg | 66ms | 73ms | 7ms | 10.65
| PostStore.GetPostsBefore | avg | 48ms | 53ms | 5ms | 10.49
| PreferenceStore.GetAll | avg | 48ms | 53ms | 5ms | 10.37
| SessionStore.GetSessionsWithActiveDeviceIds | avg | 39ms | 43ms | 4ms | 10.26
| PostPriorityStore.GetForPosts | avg | 69ms | 76ms | 7ms | 10.12
| UserStore.GetAllProfiles | avg | 30ms | 33ms | 3ms | 10.02
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | avg | 40ms | 44ms | 4ms | 9.97
| StatusStore.GetByIds | avg | 70ms | 77ms | 7ms | 9.97
| ChannelStore.GetChannelsByUser | avg | 30ms | 33ms | 3ms | 9.88
| PostStore.GetPostsSince | avg | 71ms | 78ms | 7ms | 9.81
| ThreadStore.GetMembershipForUser | avg | 51ms | 56ms | 5ms | 9.80
| ThreadStore.GetThreadFollowers | avg | 51ms | 56ms | 5ms | 9.78
| UserStore.GetUnreadCount | avg | 41ms | 45ms | 4ms | 9.74
| ChannelStore.GetGuestCount | avg | 62ms | 68ms | 6ms | 9.72
| PostStore.AnalyticsPostCount | avg | 1.493s | 1.638s | 145ms | 9.71
| FileInfoStore.GetByIds | avg | 62ms | 68ms | 6ms | 9.70
| UserStore.IsEmpty | avg | 21ms | 23ms | 2ms | 9.65
| UserStore.GetForLogin | avg | 32ms | 35ms | 3ms | 9.50
| ChannelStore.SaveMember | avg | 170ms | 186ms | 16ms | 9.42
| WebhookStore.GetOutgoingByTeam | avg | 55ms | 60ms | 5ms | 9.12
| ChannelStore.GetAllChannelMembersForUser | avg | 33ms | 36ms | 3ms | 9.12
| ThreadStore.Get | avg | 66ms | 72ms | 6ms | 9.08
| FileInfoStore.Get | avg | 33ms | 36ms | 3ms | 9.08
| GroupStore.AdminRoleGroupsForSyncableMember | avg | 33ms | 36ms | 3ms | 9.07
| ChannelBookmarkStore.GetBookmarksForChannelSince | avg | 23ms | 25ms | 2ms | 8.64
| ThreadStore.GetTotalUnreadUrgentMentions | avg | 35ms | 38ms | 3ms | 8.61
| SessionStore.Save | avg | 35ms | 38ms | 3ms | 8.54
| ThreadStore.GetThreadsForUser | avg | 59ms | 64ms | 5ms | 8.53
| ChannelStore.GetMembersForUserWithPagination | avg | 36ms | 39ms | 3ms | 8.32
| PostStore.GetPosts | avg | 24ms | 26ms | 2ms | 8.23
| ThreadStore.GetTotalUnreadMentions | avg | 37ms | 40ms | 3ms | 8.15
| ChannelStore.GetChannelUnread | avg | 38ms | 41ms | 3ms | 7.93
| ChannelStore.GetMembersForUserWithCursorPagination | avg | 89ms | 96ms | 7ms | 7.89
| ChannelStore.IsReadOnlyChannel | avg | 26ms | 28ms | 2ms | 7.78
| ThreadStore.GetThreadForUser | avg | 67ms | 72ms | 5ms | 7.47
| PostPersistentNotificationStore.GetSingle | avg | 54ms | 58ms | 4ms | 7.40
| SharedChannelStore.HasChannel | avg | 29ms | 31ms | 2ms | 6.96
| ChannelStore.GetMemberCount | avg | 235ms | 251ms | 16ms | 6.80
| ChannelStore.Get | avg | 103ms | 110ms | 7ms | 6.77
| SessionStore.GetLRUSessions | avg | 30ms | 32ms | 2ms | 6.67
| ChannelStore.GetSidebarCategory | avg | 107ms | 114ms | 7ms | 6.56
| PostStore.GetPostsByThread | avg | 52ms | 55ms | 3ms | 5.82
| UserStore.GetProfilesByUsernames | avg | 37ms | 39ms | 2ms | 5.44
| ProductNoticesStore.View | avg | 58ms | 61ms | 3ms | 5.17
| PluginStore.List | avg | 44ms | 46ms | 2ms | 4.55
| PostStore.GetPostsAfter | avg | 50ms | 52ms | 2ms | 4.04
| TeamStore.SaveMember | avg | 125ms | 130ms | 5ms | 3.99
| UserStore.GetAllProfilesInChannel | avg | 688ms | 715ms | 27ms | 3.93
| UserStore.Save | avg | 82ms | 85ms | 3ms | 3.65
| RoleStore.GetByNames | avg | 142ms | 147ms | 5ms | 3.52
| UserStore.Search | avg | 178ms | 184ms | 6ms | 3.37
| UserStore.AutocompleteUsersInChannel | avg | 378ms | 388ms | 10ms | 2.65
| UserStore.Count | avg | 179ms | 183ms | 4ms | 2.23
| ChannelStore.GetTeamChannels | avg | 111ms | 113ms | 2ms | 1.81
### Store times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ChannelBookmarkStore.Get | p99 | 240ms | 2.177s | 1.937s | 808.77
| SessionStore.GetSessionsExpired | p99 | 452ms | 2.35s | 1.898s | 419.45
| DesktopTokensStore.DeleteOlderThan | p99 | 5ms | 25ms | 20ms | 404.04
| ChannelBookmarkStore.Delete | p99 | 47ms | 231ms | 184ms | 391.48
| UserStore.GetProfilesNotInChannel | p99 | 461ms | 1.93s | 1.469s | 318.48
| JobStore.UpdateStatus | p99 | 40ms | 150ms | 110ms | 275.57
| PostStore.SetPostReminder | p99 | 78ms | 201ms | 123ms | 156.69
| DraftStore.DeleteDraftsAssociatedWithPost | p99 | 98ms | 230ms | 132ms | 134.31
| StatusStore.UpdateExpiredDNDStatuses | p99 | 98ms | 214ms | 116ms | 117.99
| ScheduledPostStore.UpdateOldScheduledPosts | p99 | 22ms | 46ms | 24ms | 110.60
| JobStore.GetCountByStatusAndType | p99 | 397ms | 820ms | 423ms | 106.64
| ChannelStore.CreateSidebarCategory | p99 | 239ms | 473ms | 234ms | 97.70
| PostPersistentNotificationStore.DeleteExpired | p99 | 32ms | 60ms | 28ms | 88.19
| PostStore.Delete | p99 | 461ms | 800ms | 339ms | 73.50
| UserStore.GetMany | p99 | 807ms | 1.382s | 575ms | 71.28
| JobStore.UpdateOptimistically | p99 | 47ms | 78ms | 31ms | 65.43
| ReactionStore.GetForPost | p99 | 588ms | 763ms | 175ms | 29.74
| DraftStore.GetDraftsForUser | p99 | 706ms | 905ms | 199ms | 28.17
| ChannelStore.GetMember | p99 | 99ms | 126ms | 27ms | 27.34
| ChannelStore.GetByName | p99 | 497ms | 632ms | 135ms | 27.16
| SessionStore.Get | p99 | 498ms | 618ms | 120ms | 24.10
| PostAcknowledgementStore.GetForPosts | p99 | 1.032s | 1.277s | 245ms | 23.74
| ClusterDiscoveryStore.SetLastPingAt | p99 | 153ms | 189ms | 36ms | 23.51
| PostPriorityStore.GetForPost | p99 | 702ms | 865ms | 163ms | 23.23
| UserStore.Save | p99 | 276ms | 336ms | 60ms | 21.74
| JobStore.GetAllByStatus | p99 | 712ms | 866ms | 154ms | 21.64
| FileInfoStore.AttachToPost | p99 | 94ms | 114ms | 20ms | 21.20
| StatusStore.Get | p99 | 619ms | 740ms | 121ms | 19.54
| PostStore.Get | p99 | 1.243s | 1.483s | 240ms | 19.31
| UserStore.GetProfileByIds | p99 | 557ms | 664ms | 107ms | 19.23
| FileInfoStore.Save | p99 | 117ms | 139ms | 22ms | 18.79
| LinkMetadataStore.Save | p99 | 86ms | 102ms | 16ms | 18.57
| UserStore.UpdateLastLogin | p99 | 61ms | 72ms | 11ms | 18.10
| SessionStore.GetSessionsWithActiveDeviceIds | p99 | 591ms | 697ms | 106ms | 17.93
| PostPriorityStore.GetForPosts | p99 | 1.152s | 1.351s | 199ms | 17.27
| ChannelStore.GetMemberCount | p99 | 1.144s | 1.329s | 185ms | 16.17
| ThreadStore.GetTotalUnreadMentions | p99 | 507ms | 589ms | 82ms | 16.17
| ChannelMemberHistoryStore.LogJoinEvent | p99 | 64ms | 74ms | 10ms | 15.69
| ChannelStore.GetChannelsWithUnreadsAndWithMentions | p99 | 573ms | 662ms | 89ms | 15.53
| PostStore.GetPostIdAfterTime | p99 | 62ms | 71ms | 9ms | 14.42
| PostStore.GetPostsBefore | p99 | 638ms | 728ms | 90ms | 14.11
| EmojiStore.GetByName | p99 | 697ms | 793ms | 96ms | 13.77
| UserStore.Get | p99 | 489ms | 555ms | 66ms | 13.50
| ChannelStore.GetMemberCountsByGroup | p99 | 143ms | 162ms | 19ms | 13.24
| UserTermsOfServiceStore.GetByUser | p99 | 495ms | 559ms | 64ms | 12.94
| UserStore.GetUnreadCount | p99 | 645ms | 727ms | 82ms | 12.71
| ChannelStore.CreateDirectChannel | p99 | 1.986s | 2.237s | 251ms | 12.64
| PreferenceStore.Get | p99 | 637ms | 717ms | 80ms | 12.56
| PostStore.GetEtag | p99 | 694ms | 780ms | 86ms | 12.39
| DraftStore.Upsert | p99 | 98ms | 110ms | 12ms | 12.23
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel | p99 | 786ms | 876ms | 90ms | 11.44
| TeamStore.GetTeamsByUserId | p99 | 484ms | 539ms | 55ms | 11.36
| UserStore.UpdateUpdateAt | p99 | 69ms | 76ms | 7ms | 10.18
| SystemStore.GetByName | p99 | 69ms | 76ms | 7ms | 10.18
| ChannelStore.UpdateLastViewedAt | p99 | 153ms | 168ms | 15ms | 9.78
| ThreadStore.GetTotalUnreadUrgentMentions | p99 | 488ms | 534ms | 46ms | 9.42
| FileInfoStore.GetForPost | p99 | 880ms | 962ms | 82ms | 9.32
| ThreadStore.GetTeamsUnreadForUser | p99 | 781ms | 853ms | 72ms | 9.22
| GroupStore.GetGroups | p99 | 739ms | 807ms | 68ms | 9.20
| JobStore.Save | p99 | 44ms | 48ms | 4ms | 9.11
| TeamStore.Get | p99 | 686ms | 748ms | 62ms | 9.03
| ProductNoticesStore.View | p99 | 412ms | 449ms | 37ms | 8.99
| WebhookStore.GetOutgoingByTeam | p99 | 740ms | 806ms | 66ms | 8.92
| LinkMetadataStore.Get | p99 | 710ms | 773ms | 63ms | 8.88
| PreferenceStore.GetAll | p99 | 667ms | 726ms | 59ms | 8.85
| ThreadStore.MarkAsRead | p99 | 80ms | 87ms | 7ms | 8.76
| ThreadStore.GetThreadUnreadReplyCount | p99 | 782ms | 849ms | 67ms | 8.57
| PostStore.GetSingle | p99 | 699ms | 758ms | 59ms | 8.44
| ChannelStore.GetChannels | p99 | 762ms | 825ms | 63ms | 8.27
| ChannelStore.GetMembersForUser | p99 | 731ms | 791ms | 60ms | 8.21
| ChannelStore.GetMemberForPost | p99 | 807ms | 873ms | 66ms | 8.18
| ThreadStore.GetMembershipForUser | p99 | 747ms | 806ms | 59ms | 7.90
| UserStore.IsEmpty | p99 | 375ms | 404ms | 29ms | 7.73
| PreferenceStore.DeleteCategoryAndName | p99 | 42ms | 45ms | 3ms | 7.10
| PostStore.GetPostsSince | p99 | 783ms | 838ms | 55ms | 7.03
| ThreadStore.GetTotalUnreadThreads | p99 | 484ms | 517ms | 33ms | 6.82
| ThreadStore.MarkAllAsReadByChannels | p99 | 89ms | 95ms | 6ms | 6.78
| DraftStore.Get | p99 | 830ms | 884ms | 54ms | 6.51
| AuditStore.Save | p99 | 79ms | 84ms | 5ms | 6.33
| PostStore.GetPostsByThread | p99 | 755ms | 802ms | 47ms | 6.23
| ThreadStore.GetThreadsForUser | p99 | 776ms | 823ms | 47ms | 6.06
| TeamStore.GetChannelUnreadsForAllTeams | p99 | 487ms | 516ms | 29ms | 5.96
| UserStore.GetForLogin | p99 | 447ms | 473ms | 26ms | 5.82
| ScheduledPostStore.GetScheduledPostsForUser | p99 | 438ms | 463ms | 25ms | 5.71
| ChannelStore.IsReadOnlyChannel | p99 | 445ms | 469ms | 24ms | 5.40
| TeamStore.GetAllPage | p99 | 477ms | 502ms | 25ms | 5.24
| PostStore.GetPosts | p99 | 401ms | 422ms | 21ms | 5.24
| ThreadStore.MaintainMembership | p99 | 193ms | 203ms | 10ms | 5.19
| ThreadStore.GetThreadFollowers | p99 | 765ms | 804ms | 39ms | 5.10
| TeamStore.GetTeamsForUser | p99 | 460ms | 483ms | 23ms | 5.00
| ChannelStore.IncrementMentionCount | p99 | 84ms | 88ms | 4ms | 4.79
| ChannelStore.SearchGroupChannels | p99 | 783ms | 820ms | 37ms | 4.73
| UserStore.Update | p99 | 213ms | 223ms | 10ms | 4.69
| StatusStore.UpdateLastActivityAt | p99 | 86ms | 90ms | 4ms | 4.66
| PostStore.GetPostIdBeforeTime | p99 | 86ms | 90ms | 4ms | 4.65
| ChannelStore.GetChannelsByUser | p99 | 452ms | 473ms | 21ms | 4.65
| ChannelStore.GetMemberLastViewedAt | p99 | 440ms | 460ms | 20ms | 4.54
| UserStore.AutocompleteUsersInChannel | p99 | 1.948s | 2.035s | 87ms | 4.47
| ChannelStore.GetAllChannelMembersForUser | p99 | 466ms | 486ms | 20ms | 4.29
| FileInfoStore.Get | p99 | 469ms | 488ms | 19ms | 4.05
| SharedChannelStore.HasChannel | p99 | 455ms | 473ms | 18ms | 3.96
| ChannelStore.GetGuestCount | p99 | 813ms | 845ms | 32ms | 3.93
| PropertyFieldStore.SearchPropertyFields | p99 | 411ms | 427ms | 16ms | 3.90
| PostPersistentNotificationStore.GetSingle | p99 | 783ms | 812ms | 29ms | 3.70
| FileInfoStore.SetContent | p99 | 191ms | 198ms | 7ms | 3.67
| ChannelBookmarkStore.GetBookmarksForChannelSince | p99 | 409ms | 423ms | 14ms | 3.42
| GroupStore.GetByName | p99 | 447ms | 462ms | 15ms | 3.36
| ThreadStore.GetTotalThreads | p99 | 484ms | 500ms | 16ms | 3.31
| UserStore.GetAllProfiles | p99 | 461ms | 476ms | 15ms | 3.25
| StatusStore.GetByIds | p99 | 861ms | 888ms | 27ms | 3.14
| ThreadStore.Get | p99 | 888ms | 914ms | 26ms | 2.93
| UserStore.GetProfilesByUsernames | p99 | 480ms | 494ms | 14ms | 2.91
| ChannelStore.Get | p99 | 929ms | 954ms | 25ms | 2.69
| ChannelStore.UpdateSidebarChannelsByPreferences | p99 | 75ms | 77ms | 2ms | 2.65
| SessionStore.UpdateLastActivityAt | p99 | 79ms | 81ms | 2ms | 2.54
| ThreadStore.GetThreadForUser | p99 | 950ms | 973ms | 23ms | 2.42
| ChannelStore.SaveMember | p99 | 2.233s | 2.287s | 54ms | 2.42
| ChannelStore.GetMembersForUserWithPagination | p99 | 487ms | 498ms | 11ms | 2.26
| ThreadStore.UpdateMembership | p99 | 90ms | 92ms | 2ms | 2.23
| PostStore.Save | p99 | 237ms | 242ms | 5ms | 2.11
| GroupStore.AdminRoleGroupsForSyncableMember | p99 | 484ms | 494ms | 10ms | 2.07
| TeamStore.GetTotalMemberCount | p99 | 922ms | 935ms | 13ms | 1.41
| PostStore.Update | p99 | 215ms | 218ms | 3ms | 1.40
| PreferenceStore.Save | p99 | 226ms | 229ms | 3ms | 1.33
| SessionStore.Save | p99 | 455ms | 461ms | 6ms | 1.32
| ChannelStore.GetMembersForUserWithCursorPagination | p99 | 950ms | 962ms | 12ms | 1.26
| UserStore.Search | p99 | 968ms | 979ms | 11ms | 1.14
### Store times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | avg | 5ms | 0s | -5ms | -103.86
| PostPersistentNotificationStore.UpdateLastActivity | avg | 4ms | 0s | -4ms | -102.83
| ChannelStore.GetChannelsByIds | avg | 24ms | 0s | -24ms | -101.63
| TeamStore.GetMany | avg | 42ms | 0s | -42ms | -101.02
| PostStore.GetPostsByIds | avg | 67ms | 0s | -67ms | -100.24
| ScheduledPostStore.Get | avg | 108ms | 2ms | -106ms | -97.85
| PluginStore.SetWithOptions | avg | 10ms | 0s | -10ms | -97.19
| PluginStore.Delete | avg | 4ms | 0s | -4ms | -90.92
| ThreadStore.MarkAllAsReadByTeam | avg | 19ms | 4ms | -15ms | -79.16
| TokenStore.Cleanup | avg | 26ms | 10ms | -16ms | -61.50
| EmojiStore.GetMultipleByName | avg | 139ms | 54ms | -85ms | -61.16
| ChannelStore.CreateInitialSidebarCategories | avg | 64ms | 28ms | -36ms | -56.07
| CommandWebhookStore.Cleanup | avg | 23ms | 15ms | -8ms | -34.40
| PostStore.GetPostReminderMetadata | avg | 57ms | 39ms | -18ms | -31.33
| LinkMetadataStore.Save | avg | 10ms | 7ms | -3ms | -29.80
| ProductNoticesStore.ClearOldNotices | avg | 7ms | 5ms | -2ms | -27.04
| ChannelStore.GetSidebarCategoriesForTeamForUser | avg | 84ms | 64ms | -20ms | -23.88
| ChannelBookmarkStore.UpdateSortOrder | avg | 116ms | 91ms | -25ms | -21.54
| UserAccessTokenStore.GetByToken | avg | 54ms | 43ms | -11ms | -20.27
| ChannelStore.GetMemberCountsByGroup | avg | 11ms | 9ms | -2ms | -18.62
| StatusStore.SaveOrUpdate | avg | 12ms | 10ms | -2ms | -16.30
| PostStore.SearchPostsForUser | avg | 121ms | 106ms | -15ms | -12.41
| ChannelStore.Save | avg | 89ms | 79ms | -10ms | -11.20
| ChannelStore.GetPublicChannelsForTeam | avg | 78ms | 71ms | -7ms | -9.01
| PropertyValueStore.SearchPropertyValues | avg | 69ms | 63ms | -6ms | -8.71
| ScheduledPostStore.GetPendingScheduledPosts | avg | 62ms | 57ms | -5ms | -8.07
| TeamStore.GetTotalMemberCount | avg | 251ms | 234ms | -17ms | -6.77
| JobStore.GetNewestJobByStatusesAndType | avg | 45ms | 43ms | -2ms | -4.40
| ChannelStore.UpdateSidebarCategories | avg | 70ms | 67ms | -3ms | -4.28
| UserStore.GetByUsername | avg | 53ms | 51ms | -2ms | -3.77
| ChannelStore.AutocompleteInTeamForSearch | avg | 278ms | 272ms | -6ms | -2.16
| ChannelStore.Autocomplete | avg | 1.509s | 1.48s | -29ms | -1.92
| TeamStore.GetActiveMemberCount | avg | 279ms | 274ms | -5ms | -1.79
### Store times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| PluginStore.Delete | p99 | 42ms | 0s | -42ms | -101.05
| PluginStore.Get | p99 | 5ms | 0s | -5ms | -101.01
| LicenseStore.GetAll | p99 | 5ms | 0s | -5ms | -101.01
| GroupStore.GetGroupsAssociatedToChannelsByTeam | p99 | 5ms | 0s | -5ms | -101.01
| PostPersistentNotificationStore.UpdateLastActivity | p99 | 5ms | 0s | -5ms | -101.00
| ScheduledPostStore.PermanentlyDeleteScheduledPosts | p99 | 10ms | 0s | -10ms | -100.97
| PluginStore.SetWithOptions | p99 | 93ms | 0s | -93ms | -100.36
| PostStore.GetPostsByIds | p99 | 490ms | 0s | -490ms | -100.00
| ChannelStore.GetChannelsByIds | p99 | 242ms | 0s | -242ms | -99.79
| TeamStore.GetMany | p99 | 242ms | 0s | -242ms | -99.79
| ScheduledPostStore.Get | p99 | 247ms | 5ms | -242ms | -97.98
| ThreadStore.MarkAllAsReadByTeam | p99 | 97ms | 10ms | -87ms | -89.46
| ScheduledPostStore.GetPendingScheduledPosts | p99 | 1.84s | 460ms | -1.38s | -75.00
| PostStore.GetPostReminderMetadata | p99 | 897ms | 240ms | -657ms | -73.20
| ChannelStore.CreateInitialSidebarCategories | p99 | 640ms | 238ms | -402ms | -62.86
| CommandWebhookStore.Cleanup | p99 | 241ms | 96ms | -145ms | -60.17
| RoleStore.ChannelHigherScopedPermissions | p99 | 2.272s | 938ms | -1.334s | -58.72
| JobStore.GetNewestJobByStatusesAndType | p99 | 1.26s | 547ms | -713ms | -56.59
| UserAccessTokenStore.GetByToken | p99 | 1.405s | 615ms | -790ms | -56.23
| PluginStore.List | p99 | 1.15s | 510ms | -640ms | -55.65
| ChannelStore.GetSidebarCategory | p99 | 1.99s | 979ms | -1.011s | -50.80
| TokenStore.Cleanup | p99 | 97ms | 48ms | -49ms | -50.52
| ChannelBookmarkStore.UpdateSortOrder | p99 | 925ms | 489ms | -436ms | -47.14
| ChannelStore.GetTeamChannels | p99 | 845ms | 481ms | -364ms | -43.08
| EmojiStore.GetMultipleByName | p99 | 800ms | 470ms | -330ms | -41.25
| PostStore.SearchPostsForUser | p99 | 1.473s | 889ms | -584ms | -39.64
| StatusStore.SaveOrUpdate | p99 | 163ms | 99ms | -64ms | -39.15
| ChannelStore.GetSidebarCategoriesForTeamForUser | p99 | 1.355s | 900ms | -455ms | -33.58
| PostPersistentNotificationStore.Get | p99 | 61ms | 43ms | -18ms | -29.51
| UserStore.GetByUsername | p99 | 714ms | 590ms | -124ms | -17.37
| BotStore.Get | p99 | 444ms | 377ms | -67ms | -15.10
| ChannelStore.Save | p99 | 928ms | 832ms | -96ms | -10.35
| UserStore.GetProfilesInChannel | p99 | 1.915s | 1.735s | -180ms | -9.40
| ChannelStore.GetPublicChannelsForTeam | p99 | 809ms | 735ms | -74ms | -9.15
| PropertyValueStore.SearchPropertyValues | p99 | 899ms | 832ms | -67ms | -7.45
| PostAcknowledgementStore.GetForPost | p99 | 783ms | 728ms | -55ms | -7.02
| JobStore.UpdateStatusOptimistically | p99 | 214ms | 200ms | -14ms | -6.55
| RoleStore.GetByNames | p99 | 919ms | 866ms | -53ms | -5.77
| ScheduledPostStore.CreateScheduledPost | p99 | 97ms | 92ms | -5ms | -5.17
| PostStore.GetPostsAfter | p99 | 805ms | 766ms | -39ms | -4.85
| TeamStore.GetActiveMemberCount | p99 | 948ms | 903ms | -45ms | -4.75
| FileInfoStore.GetByIds | p99 | 942ms | 898ms | -44ms | -4.67
| ChannelStore.GetChannelUnread | p99 | 512ms | 491ms | -21ms | -4.10
| ChannelBookmarkStore.Save | p99 | 448ms | 433ms | -15ms | -3.35
| ChannelStore.UpdateSidebarCategories | p99 | 500ms | 484ms | -16ms | -3.20
| ChannelStore.GetPinnedPostCount | p99 | 844ms | 835ms | -9ms | -1.07
### API times avg (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | avg | 83ms | 345ms | 262ms | 315.05
| getChannelMembers | avg | 63ms | 145ms | 82ms | 130.43
| deletePost | avg | 153ms | 329ms | 176ms | 115.18
| createCategoryForTeamForUser | avg | 59ms | 110ms | 51ms | 86.60
| getDrafts | avg | 58ms | 75ms | 17ms | 29.24
| getTeamMember | avg | 8ms | 10ms | 2ms | 24.69
| unfollowThreadByUser | avg | 153ms | 187ms | 34ms | 22.22
| getUsers | avg | 32ms | 39ms | 7ms | 21.85
| createDirectChannel | avg | 601ms | 702ms | 101ms | 16.80
| listCPAFields | avg | 27ms | 31ms | 4ms | 14.64
| removeUserCustomStatus | avg | 275ms | 315ms | 40ms | 14.52
| getPostThread | avg | 294ms | 336ms | 42ms | 14.27
| getTeamsUnreadForUser | avg | 65ms | 74ms | 9ms | 13.87
| getUser | avg | 59ms | 67ms | 8ms | 13.57
| getChannelsForTeamForUser | avg | 55ms | 62ms | 7ms | 12.66
| getTeamScheduledPosts | avg | 56ms | 63ms | 7ms | 12.52
| deleteDraft | avg | 64ms | 72ms | 8ms | 12.49
| getPostsForChannel | avg | 482ms | 541ms | 59ms | 12.25
| searchGroupChannels | avg | 57ms | 64ms | 7ms | 12.22
| getTeamMembersForUser | avg | 34ms | 38ms | 4ms | 11.88
| viewChannel | avg | 162ms | 181ms | 19ms | 11.72
| getChannelMembersForTeamForUser | avg | 52ms | 58ms | 6ms | 11.46
| getChannelMember | avg | 45ms | 50ms | 5ms | 11.18
| getTeamsForUser | avg | 36ms | 40ms | 4ms | 10.99
| getChannelMembersForUser | avg | 36ms | 40ms | 4ms | 10.99
| updateCategoriesForTeamForUser | avg | 330ms | 366ms | 36ms | 10.89
| getAllTeams | avg | 38ms | 42ms | 4ms | 10.64
| getPreferences | avg | 49ms | 54ms | 5ms | 10.24
| saveReaction | avg | 162ms | 178ms | 16ms | 9.85
| getChannelUnread | avg | 41ms | 45ms | 4ms | 9.78
| getChannelsForUser | avg | 31ms | 34ms | 3ms | 9.78
| getPostsForChannelAroundLastUnread | avg | 149ms | 163ms | 14ms | 9.37
| updateReadStateThreadByUser | avg | 456ms | 496ms | 40ms | 8.78
| getThreadsForUser | avg | 58ms | 63ms | 5ms | 8.68
| getChannel | avg | 105ms | 114ms | 9ms | 8.58
| getUsersByNames | avg | 37ms | 40ms | 3ms | 8.00
| createPost | avg | 976ms | 1.052s | 76ms | 7.79
| login | avg | 171ms | 184ms | 13ms | 7.60
| updatePreferences | avg | 29ms | 31ms | 2ms | 6.81
| upsertDraft | avg | 32ms | 34ms | 2ms | 6.24
| getChannelStats | avg | 32ms | 34ms | 2ms | 6.17
| addTeamMember | avg | 2.073s | 2.165s | 92ms | 4.44
| createUser | avg | 629ms | 653ms | 24ms | 3.82
| getFileThumbnail | avg | 81ms | 84ms | 3ms | 3.68
| logout | avg | 172ms | 178ms | 6ms | 3.50
| searchUsers | avg | 180ms | 185ms | 5ms | 2.77
| autocompleteUsers | avg | 339ms | 348ms | 9ms | 2.66
| getFilePreview | avg | 86ms | 88ms | 2ms | 2.34
### API times p99 (worsened):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| updateChannelBookmark | p99 | 246ms | 4.6s | 4.354s | 1768.12
| deletePost | p99 | 948ms | 2.3s | 1.352s | 142.57
| removeUserCustomStatus | p99 | 1.045s | 2.373s | 1.328s | 127.08
| getChannelMembers | p99 | 487ms | 955ms | 468ms | 96.00
| createCategoryForTeamForUser | p99 | 482ms | 945ms | 463ms | 95.96
| deleteChannelBookmark | p99 | 492ms | 950ms | 458ms | 93.00
| getTeamMember | p99 | 99ms | 159ms | 60ms | 60.67
| unfollowThreadByUser | p99 | 1.615s | 2.248s | 633ms | 39.19
| createDirectChannel | p99 | 3.304s | 4.39s | 1.086s | 32.87
| getUserStatusesByIds | p99 | 25ms | 33ms | 8ms | 32.53
| getUsers | p99 | 493ms | 610ms | 117ms | 23.71
| getDrafts | p99 | 775ms | 938ms | 163ms | 21.04
| getAllTeams | p99 | 491ms | 582ms | 91ms | 18.55
| getTeamsUnreadForUser | p99 | 961ms | 1.118s | 157ms | 16.34
| getUsersByIds | p99 | 130ms | 148ms | 18ms | 13.89
| getTeamsForUser | p99 | 485ms | 542ms | 57ms | 11.76
| getPostThread | p99 | 3.381s | 3.759s | 378ms | 11.18
| getPreferences | p99 | 682ms | 742ms | 60ms | 8.79
| getChannelMembersForTeamForUser | p99 | 731ms | 792ms | 61ms | 8.34
| getChannelsForTeamForUser | p99 | 762ms | 825ms | 63ms | 8.27
| createUser | p99 | 3.101s | 3.352s | 251ms | 8.09
| getPostsForChannel | p99 | 8.177s | 8.816s | 639ms | 7.82
| createPost | p99 | 8.1s | 8.681s | 581ms | 7.17
| getUser | p99 | 846ms | 902ms | 56ms | 6.62
| deleteDraft | p99 | 831ms | 885ms | 54ms | 6.50
| getThreadsForUser | p99 | 817ms | 861ms | 44ms | 5.38
| getTeamMembersForUser | p99 | 470ms | 494ms | 24ms | 5.11
| getChannelsForUser | p99 | 455ms | 478ms | 23ms | 5.05
| searchGroupChannels | p99 | 783ms | 820ms | 37ms | 4.73
| getTeamScheduledPosts | p99 | 864ms | 903ms | 39ms | 4.51
| login | p99 | 1.901s | 1.982s | 81ms | 4.26
| autocompleteUsers | p99 | 2.027s | 2.111s | 84ms | 4.14
| listCPAFields | p99 | 436ms | 454ms | 18ms | 4.13
| getClientConfig | p99 | 242ms | 251ms | 9ms | 3.72
| getChannelStats | p99 | 803ms | 829ms | 26ms | 3.24
| viewChannel | p99 | 2.352s | 2.428s | 76ms | 3.23
| getFilePreview | p99 | 744ms | 767ms | 23ms | 3.09
| getUsersByNames | p99 | 484ms | 498ms | 14ms | 2.89
| getChannelMember | p99 | 831ms | 855ms | 24ms | 2.89
| updateReadStateThreadByUser | p99 | 4.652s | 4.783s | 131ms | 2.82
| saveReaction | p99 | 2.166s | 2.225s | 59ms | 2.72
| getFileThumbnail | p99 | 775ms | 796ms | 21ms | 2.71
| listChannelBookmarksForChannel | p99 | 473ms | 485ms | 12ms | 2.54
| getChannelMembersForUser | p99 | 488ms | 500ms | 12ms | 2.46
| getPostsForChannelAroundLastUnread | p99 | 2.371s | 2.402s | 31ms | 1.31
### API times avg (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| deleteScheduledPost | avg | 113ms | 0s | -113ms | -99.80
| getRolesByNames | avg | 2ms | 0s | -2ms | -94.76
| updateReadStateAllThreadsByUser | avg | 19ms | 5ms | -14ms | -73.47
| followThreadByUser | avg | 182ms | 111ms | -71ms | -39.06
| createSchedulePost | avg | 33ms | 23ms | -10ms | -29.98
| createChannelBookmark | avg | 102ms | 77ms | -25ms | -24.41
| getCategoriesForTeamForUser | avg | 85ms | 66ms | -19ms | -22.34
| updateChannelBookmarkSortOrder | avg | 179ms | 142ms | -37ms | -20.67
| channelMemberCountsByGroup | avg | 34ms | 29ms | -5ms | -14.52
| listCPAValues | avg | 73ms | 65ms | -8ms | -11.00
| searchPostsInTeam | avg | 227ms | 206ms | -21ms | -9.26
| getPublicChannelsForTeam | avg | 79ms | 72ms | -7ms | -8.88
| createGroupChannel | avg | 1.245s | 1.14s | -105ms | -8.43
| getProfileImage | avg | 84ms | 77ms | -7ms | -8.34
| uploadFileStream | avg | 557ms | 531ms | -26ms | -4.67
| patchPost | avg | 400ms | 383ms | -17ms | -4.25
| deleteChannelBookmark | avg | 143ms | 139ms | -4ms | -2.79
| getTeamStats | avg | 306ms | 299ms | -7ms | -2.29
| autocompleteChannelsForTeamForSearch | avg | 278ms | 272ms | -6ms | -2.16
| addChannelMember | avg | 990ms | 970ms | -20ms | -2.02
| searchAllChannels | avg | 1.511s | 1.482s | -29ms | -1.92
### API times p99 (improved):
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| getClientLicense | p99 | 5ms | 0s | -5ms | -101.01
| deleteScheduledPost | p99 | 247ms | 0s | -247ms | -100.00
| updateReadStateAllThreadsByUser | p99 | 97ms | 10ms | -87ms | -89.46
| followThreadByUser | p99 | 2.162s | 888ms | -1.274s | -58.91
| updateChannelBookmarkSortOrder | p99 | 2.29s | 965ms | -1.325s | -57.86
| createChannelBookmark | p99 | 920ms | 461ms | -459ms | -49.89
| setPostReminder | p99 | 3.925s | 2.256s | -1.669s | -42.52
| getCategoriesForTeamForUser | p99 | 1.386s | 910ms | -476ms | -34.34
| logout | p99 | 3.275s | 2.155s | -1.12s | -34.20
| channelMemberCountsByGroup | p99 | 482ms | 408ms | -74ms | -15.35
| getChannel | p99 | 1.788s | 1.563s | -225ms | -12.59
| patchPost | p99 | 4.7s | 4.114s | -586ms | -12.47
| createGroupChannel | p99 | 9.933s | 8.814s | -1.119s | -11.27
| getPublicChannelsForTeam | p99 | 828ms | 735ms | -93ms | -11.23
| createSchedulePost | p99 | 468ms | 417ms | -51ms | -10.91
| searchPostsInTeam | p99 | 3.433s | 3.145s | -288ms | -8.39
| listCPAValues | p99 | 928ms | 853ms | -75ms | -8.09
| addChannelMember | p99 | 9.194s | 8.579s | -615ms | -6.69
| updateCategoriesForTeamForUser | p99 | 3.737s | 3.513s | -224ms | -5.99
| getChannelUnread | p99 | 585ms | 557ms | -28ms | -4.78
| updatePreferences | p99 | 304ms | 290ms | -14ms | -4.60
| uploadFileStream | p99 | 2.257s | 2.172s | -85ms | -3.77
| getProfileImage | p99 | 493ms | 486ms | -7ms | -1.42
| getTeamStats | p99 | 948ms | 935ms | -13ms | -1.37
### Store times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| AuditStore.Save |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 84ms | 5ms | 6.334
| BotStore.Get |  Avg| 34ms| 39ms | 5ms | 14.723
| |  P99| 444ms| 377ms | -67ms | -15.099
| ChannelBookmarkStore.Delete |  Avg| 10ms| 35ms | 25ms | 241.524
| |  P99| 47ms| 231ms | 184ms | 391.484
| ChannelBookmarkStore.Get |  Avg| 30ms| 129ms | 99ms | 335.396
| |  P99| 240ms| 2.177s | 1.937s | 808.768
| ChannelBookmarkStore.GetBookmarksForChannelSince |  Avg| 23ms| 25ms | 2ms | 8.645
| |  P99| 409ms| 423ms | 14ms | 3.423
| ChannelBookmarkStore.Save |  Avg| 46ms| 53ms | 7ms | 15.098
| |  P99| 448ms| 433ms | -15ms | -3.352
| ChannelBookmarkStore.UpdateSortOrder |  Avg| 116ms| 91ms | -25ms | -21.536
| |  P99| 925ms| 489ms | -436ms | -47.136
| ChannelMemberHistoryStore.LogJoinEvent |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 64ms| 74ms | 10ms | 15.695
| ChannelStore.Autocomplete |  Avg| 1.509s| 1.48s | -29ms | -1.921
| |  P99| 4.883s| 4.865s | -18ms | -0.369
| ChannelStore.AutocompleteInTeamForSearch |  Avg| 278ms| 272ms | -6ms | -2.157
| |  P99| 2.273s| 2.262s | -11ms | -0.484
| ChannelStore.CreateDirectChannel |  Avg| 178ms| 199ms | 21ms | 11.821
| |  P99| 1.986s| 2.237s | 251ms | 12.638
| ChannelStore.CreateInitialSidebarCategories |  Avg| 64ms| 28ms | -36ms | -56.074
| |  P99| 640ms| 238ms | -402ms | -62.857
| ChannelStore.CreateSidebarCategory |  Avg| 40ms| 59ms | 19ms | 47.844
| |  P99| 239ms| 473ms | 234ms | 97.704
| ChannelStore.Get |  Avg| 103ms| 110ms | 7ms | 6.774
| |  P99| 929ms| 954ms | 25ms | 2.690
| ChannelStore.GetAllChannelMembersForUser |  Avg| 33ms| 36ms | 3ms | 9.117
| |  P99| 466ms| 486ms | 20ms | 4.294
| ChannelStore.GetAllChannelMembersNotifyPropsForChannel |  Avg| 59ms| 73ms | 14ms | 23.709
| |  P99| 786ms| 876ms | 90ms | 11.445
| ChannelStore.GetByName |  Avg| 39ms| 45ms | 6ms | 15.372
| |  P99| 497ms| 632ms | 135ms | 27.156
| ChannelStore.GetChannelUnread |  Avg| 38ms| 41ms | 3ms | 7.932
| |  P99| 512ms| 491ms | -21ms | -4.104
| ChannelStore.GetChannels |  Avg| 55ms| 62ms | 7ms | 12.695
| |  P99| 762ms| 825ms | 63ms | 8.272
| ChannelStore.GetChannelsByIds |  Avg| 24ms| 0s | -24ms | -101.628
| |  P99| 242ms| 0s | -242ms | -99.794
| ChannelStore.GetChannelsByUser |  Avg| 30ms| 33ms | 3ms | 9.881
| |  P99| 452ms| 473ms | 21ms | 4.647
| ChannelStore.GetChannelsWithUnreadsAndWithMentions |  Avg| 40ms| 44ms | 4ms | 9.973
| |  P99| 573ms| 662ms | 89ms | 15.527
| ChannelStore.GetFileCount |  Avg| 36ms| 37ms | 1ms | 2.779
| |  P99| 451ms| 451ms | 0s | 0.000
| ChannelStore.GetGuestCount |  Avg| 62ms| 68ms | 6ms | 9.722
| |  P99| 813ms| 845ms | 32ms | 3.934
| ChannelStore.GetMember |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 99ms| 126ms | 27ms | 27.342
| ChannelStore.GetMemberCount |  Avg| 235ms| 251ms | 16ms | 6.804
| |  P99| 1.144s| 1.329s | 185ms | 16.174
| ChannelStore.GetMemberCountsByGroup |  Avg| 11ms| 9ms | -2ms | -18.616
| |  P99| 143ms| 162ms | 19ms | 13.245
| ChannelStore.GetMemberForPost |  Avg| 62ms| 70ms | 8ms | 12.978
| |  P99| 807ms| 873ms | 66ms | 8.179
| ChannelStore.GetMemberLastViewedAt |  Avg| 26ms| 29ms | 3ms | 11.464
| |  P99| 440ms| 460ms | 20ms | 4.543
| ChannelStore.GetMembers |  Avg| 36ms| 67ms | 31ms | 85.280
| |  P99| 475ms| 478ms | 3ms | 0.632
| ChannelStore.GetMembersForUser |  Avg| 52ms| 58ms | 6ms | 11.483
| |  P99| 731ms| 791ms | 60ms | 8.211
| ChannelStore.GetMembersForUserWithCursorPagination |  Avg| 89ms| 96ms | 7ms | 7.893
| |  P99| 950ms| 962ms | 12ms | 1.263
| ChannelStore.GetMembersForUserWithPagination |  Avg| 36ms| 39ms | 3ms | 8.317
| |  P99| 487ms| 498ms | 11ms | 2.260
| ChannelStore.GetPinnedPostCount |  Avg| 57ms| 58ms | 1ms | 1.752
| |  P99| 844ms| 835ms | -9ms | -1.066
| ChannelStore.GetPublicChannelsForTeam |  Avg| 78ms| 71ms | -7ms | -9.007
| |  P99| 809ms| 735ms | -74ms | -9.148
| ChannelStore.GetSidebarCategoriesForTeamForUser |  Avg| 84ms| 64ms | -20ms | -23.882
| |  P99| 1.355s| 900ms | -455ms | -33.584
| ChannelStore.GetSidebarCategory |  Avg| 107ms| 114ms | 7ms | 6.558
| |  P99| 1.99s| 979ms | -1.011s | -50.804
| ChannelStore.GetTeamChannels |  Avg| 111ms| 113ms | 2ms | 1.809
| |  P99| 845ms| 481ms | -364ms | -43.077
| ChannelStore.IncrementMentionCount |  Avg| 6ms| 7ms | 1ms | 16.480
| |  P99| 84ms| 88ms | 4ms | 4.789
| ChannelStore.IsReadOnlyChannel |  Avg| 26ms| 28ms | 2ms | 7.776
| |  P99| 445ms| 469ms | 24ms | 5.398
| ChannelStore.Save |  Avg| 89ms| 79ms | -10ms | -11.205
| |  P99| 928ms| 832ms | -96ms | -10.350
| ChannelStore.SaveMember |  Avg| 170ms| 186ms | 16ms | 9.418
| |  P99| 2.233s| 2.287s | 54ms | 2.418
| ChannelStore.SearchGroupChannels |  Avg| 57ms| 64ms | 7ms | 12.246
| |  P99| 783ms| 820ms | 37ms | 4.728
| ChannelStore.UpdateLastViewedAt |  Avg| 14ms| 14ms | 0s | 0.000
| |  P99| 153ms| 168ms | 15ms | 9.783
| ChannelStore.UpdateSidebarCategories |  Avg| 70ms| 67ms | -3ms | -4.279
| |  P99| 500ms| 484ms | -16ms | -3.202
| ChannelStore.UpdateSidebarChannelsByPreferences |  Avg| 5ms| 6ms | 1ms | 18.410
| |  P99| 75ms| 77ms | 2ms | 2.650
| ClusterDiscoveryStore.SetLastPingAt |  Avg| 11ms| 15ms | 4ms | 35.791
| |  P99| 153ms| 189ms | 36ms | 23.507
| CommandWebhookStore.Cleanup |  Avg| 23ms| 15ms | -8ms | -34.403
| |  P99| 241ms| 96ms | -145ms | -60.166
| DesktopTokensStore.DeleteOlderThan |  Avg| 2ms| 10ms | 8ms | 364.714
| |  P99| 5ms| 25ms | 20ms | 404.040
| DraftStore.Delete |  Avg| 10ms| 10ms | 0s | 0.000
| |  P99| 93ms| 94ms | 1ms | 1.072
| DraftStore.DeleteDraftsAssociatedWithPost |  Avg| 41ms| 46ms | 5ms | 12.140
| |  P99| 98ms| 230ms | 132ms | 134.313
| DraftStore.Get |  Avg| 63ms| 71ms | 8ms | 12.608
| |  P99| 830ms| 884ms | 54ms | 6.508
| DraftStore.GetDraftsForUser |  Avg| 54ms| 71ms | 17ms | 31.301
| |  P99| 706ms| 905ms | 199ms | 28.172
| DraftStore.Upsert |  Avg| 10ms| 11ms | 1ms | 9.775
| |  P99| 98ms| 110ms | 12ms | 12.225
| EmojiStore.GetByName |  Avg| 49ms| 55ms | 6ms | 12.254
| |  P99| 697ms| 793ms | 96ms | 13.770
| EmojiStore.GetMultipleByName |  Avg| 139ms| 54ms | -85ms | -61.164
| |  P99| 800ms| 470ms | -330ms | -41.250
| FileInfoStore.AttachToPost |  Avg| 11ms| 12ms | 1ms | 8.872
| |  P99| 94ms| 114ms | 20ms | 21.203
| FileInfoStore.Get |  Avg| 33ms| 36ms | 3ms | 9.076
| |  P99| 469ms| 488ms | 19ms | 4.050
| FileInfoStore.GetByIds |  Avg| 62ms| 68ms | 6ms | 9.703
| |  P99| 942ms| 898ms | -44ms | -4.669
| FileInfoStore.GetForPost |  Avg| 65ms| 75ms | 10ms | 15.364
| |  P99| 880ms| 962ms | 82ms | 9.318
| FileInfoStore.Save |  Avg| 11ms| 12ms | 1ms | 9.244
| |  P99| 117ms| 139ms | 22ms | 18.788
| FileInfoStore.SetContent |  Avg| 17ms| 18ms | 1ms | 5.905
| |  P99| 191ms| 198ms | 7ms | 3.673
| GroupStore.AdminRoleGroupsForSyncableMember |  Avg| 33ms| 36ms | 3ms | 9.068
| |  P99| 484ms| 494ms | 10ms | 2.067
| GroupStore.GetByName |  Avg| 31ms| 35ms | 4ms | 12.860
| |  P99| 447ms| 462ms | 15ms | 3.355
| GroupStore.GetGroups |  Avg| 51ms| 57ms | 6ms | 11.768
| |  P99| 739ms| 807ms | 68ms | 9.200
| GroupStore.GetGroupsAssociatedToChannelsByTeam |  Avg| 1ms| 0s | -1ms | -103.803
| |  P99| 5ms| 0s | -5ms | -101.010
| JobStore.GetAllByStatus |  Avg| 54ms| 61ms | 7ms | 12.976
| |  P99| 712ms| 866ms | 154ms | 21.639
| JobStore.GetCountByStatusAndType |  Avg| 35ms| 50ms | 15ms | 42.535
| |  P99| 397ms| 820ms | 423ms | 106.639
| JobStore.GetNewestJobByStatusesAndType |  Avg| 45ms| 43ms | -2ms | -4.402
| |  P99| 1.26s| 547ms | -713ms | -56.587
| JobStore.Save |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 44ms| 48ms | 4ms | 9.112
| JobStore.UpdateOptimistically |  Avg| 7ms| 9ms | 2ms | 29.297
| |  P99| 47ms| 78ms | 31ms | 65.434
| JobStore.UpdateStatus |  Avg| 7ms| 9ms | 2ms | 30.734
| |  P99| 40ms| 150ms | 110ms | 275.572
| JobStore.UpdateStatusOptimistically |  Avg| 18ms| 19ms | 1ms | 5.604
| |  P99| 214ms| 200ms | -14ms | -6.551
| LicenseStore.GetAll |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 0s | -5ms | -101.010
| LinkMetadataStore.Get |  Avg| 46ms| 52ms | 6ms | 12.927
| |  P99| 710ms| 773ms | 63ms | 8.876
| LinkMetadataStore.Save |  Avg| 10ms| 7ms | -3ms | -29.801
| |  P99| 86ms| 102ms | 16ms | 18.569
| PluginStore.Delete |  Avg| 4ms| 0s | -4ms | -90.916
| |  P99| 42ms| 0s | -42ms | -101.050
| PluginStore.Get |  Avg| 1ms| 0s | -1ms | -144.729
| |  P99| 5ms| 0s | -5ms | -101.010
| PluginStore.List |  Avg| 44ms| 46ms | 2ms | 4.555
| |  P99| 1.15s| 510ms | -640ms | -55.652
| PluginStore.SetWithOptions |  Avg| 10ms| 0s | -10ms | -97.185
| |  P99| 93ms| 0s | -93ms | -100.360
| PostAcknowledgementStore.GetForPost |  Avg| 48ms| 49ms | 1ms | 2.096
| |  P99| 783ms| 728ms | -55ms | -7.021
| PostAcknowledgementStore.GetForPosts |  Avg| 66ms| 73ms | 7ms | 10.648
| |  P99| 1.032s| 1.277s | 245ms | 23.736
| PostPersistentNotificationStore.DeleteExpired |  Avg| 3ms| 4ms | 1ms | 29.979
| |  P99| 32ms| 60ms | 28ms | 88.185
| PostPersistentNotificationStore.Get |  Avg| 4ms| 5ms | 1ms | 22.843
| |  P99| 61ms| 43ms | -18ms | -29.507
| PostPersistentNotificationStore.GetSingle |  Avg| 54ms| 58ms | 4ms | 7.403
| |  P99| 783ms| 812ms | 29ms | 3.703
| PostPersistentNotificationStore.UpdateLastActivity |  Avg| 4ms| 0s | -4ms | -102.834
| |  P99| 5ms| 0s | -5ms | -100.999
| PostPriorityStore.GetForPost |  Avg| 46ms| 53ms | 7ms | 15.264
| |  P99| 702ms| 865ms | 163ms | 23.230
| PostPriorityStore.GetForPosts |  Avg| 69ms| 76ms | 7ms | 10.122
| |  P99| 1.152s| 1.351s | 199ms | 17.270
| PostStore.AnalyticsPostCount |  Avg| 1.493s| 1.638s | 145ms | 9.711
| |  P99| 2.485s| 2.485s | 0s | 0.000
| PostStore.Delete |  Avg| 75ms| 122ms | 47ms | 62.599
| |  P99| 461ms| 800ms | 339ms | 73.496
| PostStore.Get |  Avg| 97ms| 108ms | 11ms | 11.341
| |  P99| 1.243s| 1.483s | 240ms | 19.309
| PostStore.GetEtag |  Avg| 53ms| 59ms | 6ms | 11.349
| |  P99| 694ms| 780ms | 86ms | 12.394
| PostStore.GetMaxPostSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.GetPostIdAfterTime |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 62ms| 71ms | 9ms | 14.419
| PostStore.GetPostIdBeforeTime |  Avg| 7ms| 8ms | 1ms | 13.962
| |  P99| 86ms| 90ms | 4ms | 4.652
| PostStore.GetPostReminderMetadata |  Avg| 57ms| 39ms | -18ms | -31.326
| |  P99| 897ms| 240ms | -657ms | -73.203
| PostStore.GetPostReminders |  Avg| 12ms| 12ms | 0s | 0.000
| |  P99| 89ms| 88ms | -1ms | -1.124
| PostStore.GetPosts |  Avg| 24ms| 26ms | 2ms | 8.231
| |  P99| 401ms| 422ms | 21ms | 5.238
| PostStore.GetPostsAfter |  Avg| 50ms| 52ms | 2ms | 4.039
| |  P99| 805ms| 766ms | -39ms | -4.845
| PostStore.GetPostsBefore |  Avg| 48ms| 53ms | 5ms | 10.490
| |  P99| 638ms| 728ms | 90ms | 14.112
| PostStore.GetPostsByIds |  Avg| 67ms| 0s | -67ms | -100.236
| |  P99| 490ms| 0s | -490ms | -100.000
| PostStore.GetPostsByThread |  Avg| 52ms| 55ms | 3ms | 5.823
| |  P99| 755ms| 802ms | 47ms | 6.228
| PostStore.GetPostsSince |  Avg| 71ms| 78ms | 7ms | 9.807
| |  P99| 783ms| 838ms | 55ms | 7.027
| PostStore.GetSingle |  Avg| 45ms| 50ms | 5ms | 11.099
| |  P99| 699ms| 758ms | 59ms | 8.441
| PostStore.InvalidateLastPostTimeCache |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| PostStore.Save |  Avg| 28ms| 29ms | 1ms | 3.596
| |  P99| 237ms| 242ms | 5ms | 2.112
| PostStore.SearchPostsForUser |  Avg| 121ms| 106ms | -15ms | -12.408
| |  P99| 1.473s| 889ms | -584ms | -39.645
| PostStore.SetPostReminder |  Avg| 12ms| 19ms | 7ms | 60.788
| |  P99| 78ms| 201ms | 123ms | 156.689
| PostStore.Update |  Avg| 29ms| 29ms | 0s | 0.000
| |  P99| 215ms| 218ms | 3ms | 1.398
| PreferenceStore.DeleteCategoryAndName |  Avg| 5ms| 7ms | 2ms | 36.559
| |  P99| 42ms| 45ms | 3ms | 7.101
| PreferenceStore.Get |  Avg| 44ms| 49ms | 5ms | 11.332
| |  P99| 637ms| 717ms | 80ms | 12.559
| PreferenceStore.GetAll |  Avg| 48ms| 53ms | 5ms | 10.375
| |  P99| 667ms| 726ms | 59ms | 8.851
| PreferenceStore.Save |  Avg| 22ms| 23ms | 1ms | 4.625
| |  P99| 226ms| 229ms | 3ms | 1.326
| ProductNoticesStore.ClearOldNotices |  Avg| 7ms| 5ms | -2ms | -27.037
| |  P99| 25ms| 24ms | -1ms | -4.073
| ProductNoticesStore.View |  Avg| 58ms| 61ms | 3ms | 5.166
| |  P99| 412ms| 449ms | 37ms | 8.986
| PropertyFieldStore.SearchPropertyFields |  Avg| 25ms| 28ms | 3ms | 11.893
| |  P99| 411ms| 427ms | 16ms | 3.896
| PropertyValueStore.SearchPropertyValues |  Avg| 69ms| 63ms | -6ms | -8.707
| |  P99| 899ms| 832ms | -67ms | -7.449
| ReactionStore.GetForPost |  Avg| 49ms| 49ms | 0s | 0.000
| |  P99| 588ms| 763ms | 175ms | 29.739
| RoleStore.ChannelHigherScopedPermissions |  Avg| 160ms| 159ms | -1ms | -0.624
| |  P99| 2.272s| 938ms | -1.334s | -58.723
| RoleStore.GetByNames |  Avg| 142ms| 147ms | 5ms | 3.523
| |  P99| 919ms| 866ms | -53ms | -5.766
| ScheduledPostStore.CreateScheduledPost |  Avg| 9ms| 10ms | 1ms | 11.033
| |  P99| 97ms| 92ms | -5ms | -5.168
| ScheduledPostStore.Get |  Avg| 108ms| 2ms | -106ms | -97.846
| |  P99| 247ms| 5ms | -242ms | -97.976
| ScheduledPostStore.GetMaxMessageSize |  Avg| 0s| 0s | 0s | 0.000
| |  P99| 5ms| 5ms | 0s | 0.000
| ScheduledPostStore.GetPendingScheduledPosts |  Avg| 62ms| 57ms | -5ms | -8.069
| |  P99| 1.84s| 460ms | -1.38s | -75.000
| ScheduledPostStore.GetScheduledPostsForUser |  Avg| 28ms| 32ms | 4ms | 14.347
| |  P99| 438ms| 463ms | 25ms | 5.714
| ScheduledPostStore.PermanentlyDeleteScheduledPosts |  Avg| 5ms| 0s | -5ms | -103.865
| |  P99| 10ms| 0s | -10ms | -100.969
| ScheduledPostStore.UpdateOldScheduledPosts |  Avg| 3ms| 5ms | 2ms | 63.497
| |  P99| 22ms| 46ms | 24ms | 110.599
| SessionStore.Get |  Avg| 43ms| 49ms | 6ms | 13.800
| |  P99| 498ms| 618ms | 120ms | 24.095
| SessionStore.GetLRUSessions |  Avg| 30ms| 32ms | 2ms | 6.674
| |  P99| 457ms| 456ms | -1ms | -0.219
| SessionStore.GetSessionsExpired |  Avg| 35ms| 160ms | 125ms | 357.681
| |  P99| 452ms| 2.35s | 1.898s | 419.450
| SessionStore.GetSessionsWithActiveDeviceIds |  Avg| 39ms| 43ms | 4ms | 10.255
| |  P99| 591ms| 697ms | 106ms | 17.931
| SessionStore.Remove |  Avg| 6ms| 7ms | 1ms | 15.646
| |  P99| 33ms| 33ms | 0s | 0.000
| SessionStore.Save |  Avg| 35ms| 38ms | 3ms | 8.541
| |  P99| 455ms| 461ms | 6ms | 1.317
| SessionStore.UpdateLastActivityAt |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 79ms| 81ms | 2ms | 2.540
| SharedChannelStore.HasChannel |  Avg| 29ms| 31ms | 2ms | 6.964
| |  P99| 455ms| 473ms | 18ms | 3.960
| StatusStore.Get |  Avg| 45ms| 52ms | 7ms | 15.433
| |  P99| 619ms| 740ms | 121ms | 19.537
| StatusStore.GetByIds |  Avg| 70ms| 77ms | 7ms | 9.969
| |  P99| 861ms| 888ms | 27ms | 3.137
| StatusStore.SaveOrUpdate |  Avg| 12ms| 10ms | -2ms | -16.302
| |  P99| 163ms| 99ms | -64ms | -39.146
| StatusStore.UpdateExpiredDNDStatuses |  Avg| 12ms| 16ms | 4ms | 32.125
| |  P99| 98ms| 214ms | 116ms | 117.991
| StatusStore.UpdateLastActivityAt |  Avg| 8ms| 9ms | 1ms | 12.017
| |  P99| 86ms| 90ms | 4ms | 4.658
| SystemStore.GetByName |  Avg| 5ms| 5ms | 0s | 0.000
| |  P99| 69ms| 76ms | 7ms | 10.175
| TeamStore.Get |  Avg| 44ms| 49ms | 5ms | 11.431
| |  P99| 686ms| 748ms | 62ms | 9.032
| TeamStore.GetActiveMemberCount |  Avg| 279ms| 274ms | -5ms | -1.790
| |  P99| 948ms| 903ms | -45ms | -4.745
| TeamStore.GetAllPage |  Avg| 35ms| 39ms | 4ms | 11.503
| |  P99| 477ms| 502ms | 25ms | 5.239
| TeamStore.GetChannelUnreadsForAllTeams |  Avg| 36ms| 40ms | 4ms | 11.214
| |  P99| 487ms| 516ms | 29ms | 5.956
| TeamStore.GetMany |  Avg| 42ms| 0s | -42ms | -101.016
| |  P99| 242ms| 0s | -242ms | -99.794
| TeamStore.GetMember |  Avg| 13ms| 15ms | 2ms | 14.993
| |  P99| 249ms| 248ms | -1ms | -0.402
| TeamStore.GetTeamsByUserId |  Avg| 36ms| 40ms | 4ms | 11.037
| |  P99| 484ms| 539ms | 55ms | 11.364
| TeamStore.GetTeamsForUser |  Avg| 32ms| 36ms | 4ms | 12.504
| |  P99| 460ms| 483ms | 23ms | 4.998
| TeamStore.GetTotalMemberCount |  Avg| 251ms| 234ms | -17ms | -6.775
| |  P99| 922ms| 935ms | 13ms | 1.409
| TeamStore.SaveMember |  Avg| 125ms| 130ms | 5ms | 3.992
| |  P99| 763ms| 769ms | 6ms | 0.787
| ThreadStore.Get |  Avg| 66ms| 72ms | 6ms | 9.077
| |  P99| 888ms| 914ms | 26ms | 2.927
| ThreadStore.GetMembershipForUser |  Avg| 51ms| 56ms | 5ms | 9.797
| |  P99| 747ms| 806ms | 59ms | 7.897
| ThreadStore.GetTeamsUnreadForUser |  Avg| 46ms| 53ms | 7ms | 15.239
| |  P99| 781ms| 853ms | 72ms | 9.225
| ThreadStore.GetThreadFollowers |  Avg| 51ms| 56ms | 5ms | 9.784
| |  P99| 765ms| 804ms | 39ms | 5.099
| ThreadStore.GetThreadForUser |  Avg| 67ms| 72ms | 5ms | 7.466
| |  P99| 950ms| 973ms | 23ms | 2.421
| ThreadStore.GetThreadUnreadReplyCount |  Avg| 55ms| 61ms | 6ms | 10.938
| |  P99| 782ms| 849ms | 67ms | 8.568
| ThreadStore.GetThreadsForUser |  Avg| 59ms| 64ms | 5ms | 8.534
| |  P99| 776ms| 823ms | 47ms | 6.056
| ThreadStore.GetTotalThreads |  Avg| 34ms| 38ms | 4ms | 11.597
| |  P99| 484ms| 500ms | 16ms | 3.308
| ThreadStore.GetTotalUnreadMentions |  Avg| 37ms| 40ms | 3ms | 8.154
| |  P99| 507ms| 589ms | 82ms | 16.171
| ThreadStore.GetTotalUnreadThreads |  Avg| 34ms| 38ms | 4ms | 11.667
| |  P99| 484ms| 517ms | 33ms | 6.819
| ThreadStore.GetTotalUnreadUrgentMentions |  Avg| 35ms| 38ms | 3ms | 8.615
| |  P99| 488ms| 534ms | 46ms | 9.421
| ThreadStore.MaintainMembership |  Avg| 16ms| 16ms | 0s | 0.000
| |  P99| 193ms| 203ms | 10ms | 5.194
| ThreadStore.MarkAllAsReadByChannels |  Avg| 7ms| 8ms | 1ms | 14.966
| |  P99| 89ms| 95ms | 6ms | 6.776
| ThreadStore.MarkAllAsReadByTeam |  Avg| 19ms| 4ms | -15ms | -79.159
| |  P99| 97ms| 10ms | -87ms | -89.460
| ThreadStore.MarkAsRead |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 80ms| 87ms | 7ms | 8.762
| ThreadStore.UpdateMembership |  Avg| 9ms| 9ms | 0s | 0.000
| |  P99| 90ms| 92ms | 2ms | 2.234
| TokenStore.Cleanup |  Avg| 26ms| 10ms | -16ms | -61.503
| |  P99| 97ms| 48ms | -49ms | -50.515
| UserAccessTokenStore.GetByToken |  Avg| 54ms| 43ms | -11ms | -20.271
| |  P99| 1.405s| 615ms | -790ms | -56.228
| UserStore.AutocompleteUsersInChannel |  Avg| 378ms| 388ms | 10ms | 2.646
| |  P99| 1.948s| 2.035s | 87ms | 4.466
| UserStore.Count |  Avg| 179ms| 183ms | 4ms | 2.234
| |  P99| 857ms| 858ms | 1ms | 0.117
| UserStore.Get |  Avg| 33ms| 37ms | 4ms | 12.113
| |  P99| 489ms| 555ms | 66ms | 13.503
| UserStore.GetAllProfiles |  Avg| 30ms| 33ms | 3ms | 10.015
| |  P99| 461ms| 476ms | 15ms | 3.252
| UserStore.GetAllProfilesInChannel |  Avg| 688ms| 715ms | 27ms | 3.925
| |  P99| 2.443s| 2.449s | 6ms | 0.246
| UserStore.GetByUsername |  Avg| 53ms| 51ms | -2ms | -3.769
| |  P99| 714ms| 590ms | -124ms | -17.367
| UserStore.GetForLogin |  Avg| 32ms| 35ms | 3ms | 9.497
| |  P99| 447ms| 473ms | 26ms | 5.821
| UserStore.GetMany |  Avg| 52ms| 78ms | 26ms | 50.081
| |  P99| 807ms| 1.382s | 575ms | 71.281
| UserStore.GetProfileByIds |  Avg| 39ms| 45ms | 6ms | 15.266
| |  P99| 557ms| 664ms | 107ms | 19.225
| UserStore.GetProfilesByUsernames |  Avg| 37ms| 39ms | 2ms | 5.445
| |  P99| 480ms| 494ms | 14ms | 2.914
| UserStore.GetProfilesInChannel |  Avg| 89ms| 89ms | 0s | 0.000
| |  P99| 1.915s| 1.735s | -180ms | -9.400
| UserStore.GetProfilesNotInChannel |  Avg| 42ms| 218ms | 176ms | 417.492
| |  P99| 461ms| 1.93s | 1.469s | 318.482
| UserStore.GetUnreadCount |  Avg| 41ms| 45ms | 4ms | 9.744
| |  P99| 645ms| 727ms | 82ms | 12.712
| UserStore.IsEmpty |  Avg| 21ms| 23ms | 2ms | 9.648
| |  P99| 375ms| 404ms | 29ms | 7.730
| UserStore.Save |  Avg| 82ms| 85ms | 3ms | 3.654
| |  P99| 276ms| 336ms | 60ms | 21.744
| UserStore.Search |  Avg| 178ms| 184ms | 6ms | 3.369
| |  P99| 968ms| 979ms | 11ms | 1.136
| UserStore.Update |  Avg| 21ms| 21ms | 0s | 0.000
| |  P99| 213ms| 223ms | 10ms | 4.692
| UserStore.UpdateFailedPasswordAttempts |  Avg| 8ms| 8ms | 0s | 0.000
| |  P99| 84ms| 83ms | -1ms | -1.197
| UserStore.UpdateLastLogin |  Avg| 7ms| 7ms | 0s | 0.000
| |  P99| 61ms| 72ms | 11ms | 18.103
| UserStore.UpdateUpdateAt |  Avg| 7ms| 8ms | 1ms | 13.847
| |  P99| 69ms| 76ms | 7ms | 10.176
| UserTermsOfServiceStore.GetByUser |  Avg| 37ms| 41ms | 4ms | 10.745
| |  P99| 495ms| 559ms | 64ms | 12.939
| WebhookStore.GetOutgoingByTeam |  Avg| 55ms| 60ms | 5ms | 9.122
| |  P99| 740ms| 806ms | 66ms | 8.920
### API times:
| | | Base | Actual | Delta | Delta % |
| --- | --- | --- | --- | --- | --- |
| addChannelMember | Avg| 990ms| 970ms | -20ms | -2.020
| | P99| 9.194s| 8.579s | -615ms | -6.689
| addTeamMember | Avg| 2.073s| 2.165s | 92ms | 4.437
| | P99| 10s| 10s | 0s | 0.000
| autocompleteChannelsForTeamForSearch | Avg| 278ms| 272ms | -6ms | -2.156
| | P99| 2.273s| 2.262s | -11ms | -0.484
| autocompleteUsers | Avg| 339ms| 348ms | 9ms | 2.655
| | P99| 2.027s| 2.111s | 84ms | 4.145
| channelMemberCountsByGroup | Avg| 34ms| 29ms | -5ms | -14.519
| | P99| 482ms| 408ms | -74ms | -15.347
| createCategoryForTeamForUser | Avg| 59ms| 110ms | 51ms | 86.599
| | P99| 482ms| 945ms | 463ms | 95.959
| createChannel | Avg| 1.028s| 1.032s | 4ms | 0.389
| | P99| 4.806s| 4.805s | -1ms | -0.021
| createChannelBookmark | Avg| 102ms| 77ms | -25ms | -24.407
| | P99| 920ms| 461ms | -459ms | -49.891
| createDirectChannel | Avg| 601ms| 702ms | 101ms | 16.797
| | P99| 3.304s| 4.39s | 1.086s | 32.873
| createGroupChannel | Avg| 1.245s| 1.14s | -105ms | -8.434
| | P99| 9.933s| 8.814s | -1.119s | -11.265
| createPost | Avg| 976ms| 1.052s | 76ms | 7.790
| | P99| 8.1s| 8.681s | 581ms | 7.173
| createSchedulePost | Avg| 33ms| 23ms | -10ms | -29.984
| | P99| 468ms| 417ms | -51ms | -10.909
| createUser | Avg| 629ms| 653ms | 24ms | 3.817
| | P99| 3.101s| 3.352s | 251ms | 8.094
| deleteChannelBookmark | Avg| 143ms| 139ms | -4ms | -2.790
| | P99| 492ms| 950ms | 458ms | 92.995
| deleteDraft | Avg| 64ms| 72ms | 8ms | 12.488
| | P99| 831ms| 885ms | 54ms | 6.496
| deletePost | Avg| 153ms| 329ms | 176ms | 115.184
| | P99| 948ms| 2.3s | 1.352s | 142.566
| deleteScheduledPost | Avg| 113ms| 0s | -113ms | -99.797
| | P99| 247ms| 0s | -247ms | -100.000
| followThreadByUser | Avg| 182ms| 111ms | -71ms | -39.064
| | P99| 2.162s| 888ms | -1.274s | -58.913
| getAllTeams | Avg| 38ms| 42ms | 4ms | 10.643
| | P99| 491ms| 582ms | 91ms | 18.552
| getCategoriesForTeamForUser | Avg| 85ms| 66ms | -19ms | -22.345
| | P99| 1.386s| 910ms | -476ms | -34.345
| getChannel | Avg| 105ms| 114ms | 9ms | 8.580
| | P99| 1.788s| 1.563s | -225ms | -12.587
| getChannelMember | Avg| 45ms| 50ms | 5ms | 11.182
| | P99| 831ms| 855ms | 24ms | 2.889
| getChannelMembers | Avg| 63ms| 145ms | 82ms | 130.427
| | P99| 487ms| 955ms | 468ms | 96.000
| getChannelMembersForTeamForUser | Avg| 52ms| 58ms | 6ms | 11.455
| | P99| 731ms| 792ms | 61ms | 8.344
| getChannelMembersForUser | Avg| 36ms| 40ms | 4ms | 10.994
| | P99| 488ms| 500ms | 12ms | 2.457
| getChannelStats | Avg| 32ms| 34ms | 2ms | 6.169
| | P99| 803ms| 829ms | 26ms | 3.237
| getChannelUnread | Avg| 41ms| 45ms | 4ms | 9.780
| | P99| 585ms| 557ms | -28ms | -4.784
| getChannelsForTeamForUser | Avg| 55ms| 62ms | 7ms | 12.665
| | P99| 762ms| 825ms | 63ms | 8.273
| getChannelsForUser | Avg| 31ms| 34ms | 3ms | 9.780
| | P99| 455ms| 478ms | 23ms | 5.053
| getClientConfig | Avg| 19ms| 20ms | 1ms | 5.296
| | P99| 242ms| 251ms | 9ms | 3.724
| getClientLicense | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 0s | -5ms | -101.010
| getDrafts | Avg| 58ms| 75ms | 17ms | 29.244
| | P99| 775ms| 938ms | 163ms | 21.045
| getFilePreview | Avg| 86ms| 88ms | 2ms | 2.337
| | P99| 744ms| 767ms | 23ms | 3.093
| getFileThumbnail | Avg| 81ms| 84ms | 3ms | 3.684
| | P99| 775ms| 796ms | 21ms | 2.708
| getPostThread | Avg| 294ms| 336ms | 42ms | 14.267
| | P99| 3.381s| 3.759s | 378ms | 11.179
| getPostsForChannel | Avg| 482ms| 541ms | 59ms | 12.249
| | P99| 8.177s| 8.816s | 639ms | 7.815
| getPostsForChannelAroundLastUnread | Avg| 149ms| 163ms | 14ms | 9.367
| | P99| 2.371s| 2.402s | 31ms | 1.308
| getPreferences | Avg| 49ms| 54ms | 5ms | 10.241
| | P99| 682ms| 742ms | 60ms | 8.792
| getProfileImage | Avg| 84ms| 77ms | -7ms | -8.338
| | P99| 493ms| 486ms | -7ms | -1.420
| getPublicChannelsForTeam | Avg| 79ms| 72ms | -7ms | -8.882
| | P99| 828ms| 735ms | -93ms | -11.232
| getRolesByNames | Avg| 2ms| 0s | -2ms | -94.763
| | P99| 5ms| 5ms | 0s | 0.000
| getTeamMember | Avg| 8ms| 10ms | 2ms | 24.694
| | P99| 99ms| 159ms | 60ms | 60.668
| getTeamMembersForUser | Avg| 34ms| 38ms | 4ms | 11.882
| | P99| 470ms| 494ms | 24ms | 5.112
| getTeamScheduledPosts | Avg| 56ms| 63ms | 7ms | 12.516
| | P99| 864ms| 903ms | 39ms | 4.512
| getTeamStats | Avg| 306ms| 299ms | -7ms | -2.288
| | P99| 948ms| 935ms | -13ms | -1.371
| getTeamsForUser | Avg| 36ms| 40ms | 4ms | 10.994
| | P99| 485ms| 542ms | 57ms | 11.764
| getTeamsUnreadForUser | Avg| 65ms| 74ms | 9ms | 13.868
| | P99| 961ms| 1.118s | 157ms | 16.335
| getThreadsForUser | Avg| 58ms| 63ms | 5ms | 8.680
| | P99| 817ms| 861ms | 44ms | 5.384
| getUser | Avg| 59ms| 67ms | 8ms | 13.568
| | P99| 846ms| 902ms | 56ms | 6.617
| getUserStatus | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| getUserStatusesByIds | Avg| 2ms| 2ms | 0s | 0.000
| | P99| 25ms| 33ms | 8ms | 32.527
| getUsers | Avg| 32ms| 39ms | 7ms | 21.847
| | P99| 493ms| 610ms | 117ms | 23.710
| getUsersByIds | Avg| 5ms| 6ms | 1ms | 19.359
| | P99| 130ms| 148ms | 18ms | 13.887
| getUsersByNames | Avg| 37ms| 40ms | 3ms | 8.000
| | P99| 484ms| 498ms | 14ms | 2.890
| getWebappPlugins | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| listCPAFields | Avg| 27ms| 31ms | 4ms | 14.637
| | P99| 436ms| 454ms | 18ms | 4.128
| listCPAValues | Avg| 73ms| 65ms | -8ms | -10.998
| | P99| 928ms| 853ms | -75ms | -8.086
| listChannelBookmarksForChannel | Avg| 28ms| 29ms | 1ms | 3.631
| | P99| 473ms| 485ms | 12ms | 2.537
| login | Avg| 171ms| 184ms | 13ms | 7.601
| | P99| 1.901s| 1.982s | 81ms | 4.262
| logout | Avg| 172ms| 178ms | 6ms | 3.497
| | P99| 3.275s| 2.155s | -1.12s | -34.199
| patchPost | Avg| 400ms| 383ms | -17ms | -4.249
| | P99| 4.7s| 4.114s | -586ms | -12.468
| removeUserCustomStatus | Avg| 275ms| 315ms | 40ms | 14.523
| | P99| 1.045s| 2.373s | 1.328s | 127.080
| root | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| saveReaction | Avg| 162ms| 178ms | 16ms | 9.847
| | P99| 2.166s| 2.225s | 59ms | 2.724
| searchAllChannels | Avg| 1.511s| 1.482s | -29ms | -1.919
| | P99| 4.887s| 4.865s | -22ms | -0.450
| searchGroupChannels | Avg| 57ms| 64ms | 7ms | 12.218
| | P99| 783ms| 820ms | 37ms | 4.728
| searchPostsInTeam | Avg| 227ms| 206ms | -21ms | -9.260
| | P99| 3.433s| 3.145s | -288ms | -8.388
| searchUsers | Avg| 180ms| 185ms | 5ms | 2.772
| | P99| 972ms| 981ms | 9ms | 0.926
| setPostReminder | Avg| 233ms| 232ms | -1ms | -0.430
| | P99| 3.925s| 2.256s | -1.669s | -42.523
| submitPerformanceReport | Avg| 0s| 0s | 0s | 0.000
| | P99| 5ms| 5ms | 0s | 0.000
| unfollowThreadByUser | Avg| 153ms| 187ms | 34ms | 22.219
| | P99| 1.615s| 2.248s | 633ms | 39.195
| updateCategoriesForTeamForUser | Avg| 330ms| 366ms | 36ms | 10.894
| | P99| 3.737s| 3.513s | -224ms | -5.993
| updateChannelBookmark | Avg| 83ms| 345ms | 262ms | 315.045
| | P99| 246ms| 4.6s | 4.354s | 1768.123
| updateChannelBookmarkSortOrder | Avg| 179ms| 142ms | -37ms | -20.670
| | P99| 2.29s| 965ms | -1.325s | -57.859
| updatePreferences | Avg| 29ms| 31ms | 2ms | 6.810
| | P99| 304ms| 290ms | -14ms | -4.603
| updateReadStateAllThreadsByUser | Avg| 19ms| 5ms | -14ms | -73.474
| | P99| 97ms| 10ms | -87ms | -89.460
| updateReadStateThreadByUser | Avg| 456ms| 496ms | 40ms | 8.781
| | P99| 4.652s| 4.783s | 131ms | 2.816
| updateUserCustomStatus | Avg| 0s| 1ms | 1ms | 857.131
| | P99| 5ms| 5ms | 0s | 0.000
| uploadFileStream | Avg| 557ms| 531ms | -26ms | -4.667
| | P99| 2.257s| 2.172s | -85ms | -3.766
| upsertDraft | Avg| 32ms| 34ms | 2ms | 6.237
| | P99| 496ms| 496ms | 0s | 0.000
| viewChannel | Avg| 162ms| 181ms | 19ms | 11.725
| | P99| 2.352s| 2.428s | 76ms | 3.231
